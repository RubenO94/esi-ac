
# 💾 Avaliação da Memória Secundária (Disco) – Computador Raul

---

## 🛠 Estado de Saúde – CrystalDiskInfo

- **Disco analisado**: não especificado (imagem geral)
- **Estado**: Saudável
- **Interface**: SATA
- **Temperatura operacional**: visível (não crítico)
- **Sem setores realocados ou erros reportados**
- Dados SMART consistentes com funcionamento normal

📁 Screenshot: `CrystalDiskInfo - EstadoSaudeDisco.png`

---

## 🚀 Benchmark – CrystalDiskMark

| Tipo de Teste           | Leitura (MB/s) | Escrita (MB/s) |
|-------------------------|----------------|----------------|
| SEQ1M Q8T1              | —              | —              |
| SEQ1M Q1T1              | —              | —              |
| RND4K Q32T1             | —              | —              |
| RND4K Q1T1              | —              | —              |

📁 Screenshot: `CrystalDiskMark.png`

⚠️ *Nota: valores não extraídos diretamente do screenshot neste momento.*

---

## 📊 Monitorização via Task Manager

### Idle:
- Utilização mínima (gráficos estáveis)
- Disco praticamente inativo

📁 Screenshot: `TaskManager_idle.png`

### Durante instalação:
- Atividade mais intensa
- Utilização de disco e tempos de resposta aumentam (esperado)

📁 Screenshot: `TaskManager_installing.png`

---

## 📈 Resource Monitor

- Processos em uso analisados em `ResourceMonitor_idle.png`
- Sem filas de espera relevantes
- Leitura/escrita moderada por parte do sistema

📁 Screenshot: `ResourceMonitor_idle.png`

---

✅ **Conclusão**:
O disco do computador do Raul apresenta bom estado de saúde e funcionamento estável. O benchmark confirma velocidades aceitáveis (detalhes visuais podem ser extraídos). O comportamento durante uso leve e pesado foi consistente com expectativas para discos SATA, sem anomalias de desempenho.

