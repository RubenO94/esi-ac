
# 🧠 Avaliação do Desempenho – CPU

---

## 📊 Task Manager – Monitorização em Diferentes Cargas

### Cenário 1: Idle (Sistema inativo)
- Utilização média: 15%
- Frequência: 4,30 GHz
- Processos ativos: 200
- Threads: 2.682

📁 Screenshot: `cpu_idle.png`

### Cenário 2: Carga Leve (apps, browser)
- Utilização média: 54%
- Frequência: 4,19 GHz
- Processos ativos: 243
- Threads: 3.568

📁 Screenshot: `cpu_leve.png`

### Cenário 3: Carga Alta (stress/simulação)
- Utilização média: 88%
- Frequência: 4,18 GHz
- Processos ativos: 280
- Threads: 4.491

📁 Screenshot: `cpu_pesado.png`

---

## 📈 Resource Monitor – Processos Ativos

### Processos com maior uso de CPU:
| Processo                  | Threads | CPU Média (%) |
|---------------------------|---------|----------------|
| LeagueClientUxRender.exe | 20      | 7,21%          |
| League of Legends         | 56      | 2,67%          |
| perfmon.exe               | 10      | 2,03%          |
| WMI Provider Host         | 21      | 1,84%          |
| Sistema                   | 12      | 0,74%          |
| TranslucentTB             | 13      | 0,73%          |

📁 Screenshot: `cpu_resmon.png`

---

## 🧪 Benchmark – PassMark CPU Mark

- CPU: Intel Core i7-4790K @ 4.00 GHz
- Pontuação Total (CPU Mark): 7395
- Percentil Global: 26%
- Média Mundial: 19.157
- Máximo Mundial: 189.698

### Resultados Detalhados:
| Teste                         | Resultado |
|------------------------------|-----------|
| Integer Math                 | 27.216    |
| Floating Point Math          | 14.144    |
| Prime Numbers                | 25        |
| Compression                  | 119.357   |
| Physics                      | 421       |
| CPU Single Threaded          | 2.337     |
| Extended Instructions (SSE) | 7.628     |
| Encryption                   | 2.026     |
| Sorting                      | 14.616    |

📁 Screenshot: `cpu_passmark.png`

---

✅ **Conclusão**: O processador demonstrou boa capacidade de resposta em todos os níveis de carga, com comportamento estável e sem throttling. Os resultados do benchmark são sólidos, com bom desempenho em tarefas matemáticas e compressão, apesar de estar ligeiramente abaixo da média global atual.
