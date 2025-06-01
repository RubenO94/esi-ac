# 💾 Avaliação da Memória Secundária (Disco) – Computador Raul

---

## 🛠 Estado de Saúde – CrystalDiskInfo

- **Disco analisado**: WDC PC SN530 SDBPNPZ-512G-1027 : 512,1 GB
- **Estado**: Saudável (100%)
- **Interface**: NVM Express
- **Temperatura operacional**: 43 °C
- **Firmware**: 21117000
- **Nº Vezes Ligado**: 720 vezes
- **Nº Horas Ligado**: 213 horas
- **Sem setores realocados ou erros reportados**
- Dados SMART consistentes com funcionamento normal

📁 Screenshot: `CrystalDiskInfo - EstadoSaudeDisco.png`

---

## 🚀 Benchmark – CrystalDiskMark

| Tipo de Teste | Leitura (MB/s) | Escrita (MB/s) |
|---|---|---|
| SEQ1M Q8T1 | 2435.93 | 1727.97 |
| SEQ1M Q1T1 | 1349.52 | 1577.65 |
| RND4K Q32T1 | 107.28 | 79.49 |
| RND4K Q1T1 | 23.35 | 59.90 |

📁 Screenshot: `CrystalDiskMark.png`

---

## 📊 Monitorização via Task Manager

### Idle:
- Disco 0 (C: D:) WDC PC SN530 SDBPNPZ-512G-1027
- Tempo ativo: 4%
- Tempo de resposta médio: 37,7 ms
- Velocidade de leitura: 32,1 KB/s
- Velocidade de escrita: 16,0 KB/s
- Capacidade: 477 GB
- Tipo: SSD (NVMe)
- Utilização mínima (gráficos estáveis)
- Disco praticamente inativo

📁 Screenshot: `TaskManager_idle.png`

### Durante instalação:
- Disco 0 (C: D:) WDC PC SN530 SDBPNPZ-512G-1027
- Tempo ativo: 5%
- Tempo de resposta médio: 53,8 ms
- Velocidade de leitura: 0 KB/s
- Velocidade de escrita: 23,8 MB/s
- Atividade mais intensa
- Utilização de disco e tempos de resposta aumentam (esperado)

📁 Screenshot: `TaskManager_installing.png`

---

## 📈 Resource Monitor

- Processos com Atividade de Disco: System, Registry, msedgewebview2.exe, HixviewService.exe, PickerHost.exe, explorer.exe
- Escrita (B/seg): System (122 311 B/seg), Registry (55 029 B/seg)
- Sem filas de espera relevantes (Comprimento da Fila de Disco: 0.1)
- Leitura/escrita moderada por parte do sistema

📁 Screenshot: `ResourceMonitor_idle.png`

---

✅ **Conclusão**:
O disco NVMe WDC PC SN530 SDBPNPZ-512G-1027 de 512,1 GB do computador do Raul apresenta um estado de saúde excelente e um funcionamento estável. Os resultados do CrystalDiskMark confirmam velocidades de leitura sequencial de até 2435.93 MB/s e escrita de até 1727.97 MB/s, o que é consistente com o esperado para SSDs NVMe. A monitorização via Task Manager e Resource Monitor mostra um comportamento adequado do disco tanto em idle quanto sob carga, com atividades de leitura/escrita esperadas durante instalações e operações do sistema, sem anomalias de desempenho.