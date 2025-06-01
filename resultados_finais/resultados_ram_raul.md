
# 🧠 Avaliação da Memória Principal (RAM) – Computador Raul

---

## 📊 Task Manager – Uso de Memória

### 🧘 Situação Idle:
- Capacidade total: 16,0 GB
- Em uso: 5,8 GB (3,8 MB comprimido)
- Disponível: 8,7 GB
- Em cache: 5,4 GB
- Velocidade: 2400 MT/s
- Ranhuras utilizadas: 2 de 2
- Fator de forma: SODIMM
- Reservada ao hardware: 1,1 GB

📁 Screenshot: `TaskManager_idle.png`

### 🧩 Múltiplas Aplicações Abertas:
- Em uso: 7,6 GB (42,9 MB comprimido)
- Disponível: 7,2 GB
- Em cache: 5,9 GB
- Alocada: 8,5 / 26,9 GB

📁 Screenshot: `TaskManager_multiple_open_apps.png`

---

## 📈 Resource Monitor – Detalhes da Memória

### Idle:
- Em utilização: 7.014 MB
- Em espera: 5.591 MB
- Livre: 2.555 MB
- Em cache: 5.725 MB
- Modificado: 134 MB

📁 Screenshot: `ResourceMonitor_idle.png`

### Com múltiplas aplicações:
- Em utilização: 7.948 MB
- Em espera: 6.049 MB
- Livre: 1.131 MB
- Em cache: 6.218 MB
- Modificado: 169 MB

📁 Screenshot: `ResourceMonitor_multiple_open_apps.png`

---

## 🛠 Diagnóstico – Windows Memory Diagnostic

- Teste completo realizado com 2 ciclos
- Nenhum erro detetado
- Páginas testadas: 3.883.126
- Tamanho total testado: ~15 GB
- Logs do sistema confirmam sucesso do teste

📁 Screenshots:
- `MemoryDiagnostics-OnGoing.jpg`
- `MemoryDiagnostics-Results(General).png`
- `MemoryDiagnostics-Results(Detailed).xml`

---

## 🧪 Benchmark – PassMark Memory Mark

- Score: 1409
- Percentil Global: 6%
- Média Global: 2725

### Resultados Detalhados:
| Teste                 | Resultado     |
|------------------------|---------------|
| Database Ops           | 1541 ops/s
| Read Uncached          | 10.619 MB/s
| Read Cached            | 15.717 MB/s
| Write                  | 4.996 MB/s
| Latência               | 97 ns
| Threaded Read          | 22.369 MB/s

📁 Screenshot: `PerformanceTest.png`

---

✅ **Conclusão**:
A memória RAM do computador do Raul apresenta estabilidade e uso equilibrado em diferentes cargas. Apesar de o benchmark indicar performance abaixo da média global, a latência e a largura de banda são suficientes para uso profissional comum e multitarefa.
