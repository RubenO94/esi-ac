# 🧠 Avaliação do Desempenho – CPU

---

## 📊 Task Manager – Monitorização em Diferentes Cargas

### Cenário 1: Idle (Sistema inativo)
- Utilização: 14%
- Frequência: 1,40 GHz
- Processos ativos: 231
- Threads: 2921

📁 Screenshot: `TaskManager_idle.png`

### Cenário 2: Carga Leve (apps, browser)
- Utilização: 38%
- Frequência: 2,27 GHz
- Processos ativos: 234
- Threads: 2985

📁 Screenshot: `TaskManager_word_aberto.png`

### Cenário 3: Carga Alta (stress/simulação)
- Utilização: 94%
- Frequência: 2,99 GHz
- Processos ativos: 231
- Threads: 2768

📁 Screenshot: `TaskManager_abrir_pagina_web.png`

---

## 📈 Resource Monitor – Processos Ativos

### Processos com maior uso de CPU:
| Processo | Threads | CPU Média (%) |
|---|---|---|
| chrome.exe | 2 | 9.64 |
| System | 321 | 7.36 |
| chrome.exe | 51 | 7.34 |
| perfmon.exe | 20 | 6.77 |
| backgroundTaskHost.exe | 1 | 2 |
| ShellExperienceHost.exe | 19 | 0 |

📁 Screenshot: `resmon.png`

---

## 🧪 Benchmark – PassMark CPU Mark

- CPU: AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx
- Pontuação Total (CPU Mark): 7496
- Percentil Global: 26%
- Média Mundial: 19181
- Máximo Mundial: 189698

### Resultados Detalhados:
| Teste | Resultado |
|---|---|
| Integer Math | 24487 |
| Floating Point Math | 12396 |
| Prime Numbers | 16 |
| Compression | 105439 |
| Physics | 396 |
| CPU Single Threaded | 2098 |
| Extended Instructions (SSE) | 4121 |
| Encryption | 7261 |
| Sorting | 11743 |

📁 Screenshot: `PassMark.png`

---

✅ **Conclusão**: O processador AMD Ryzen 7 3700U com Radeon Vega Mobile Gfx demonstra um bom desempenho sob diferentes cargas, atingindo 94% de utilização em carga alta com uma frequência de 2.99 GHz. O benchmark PassMark CPU Mark revela uma pontuação de 7496, colocando-o no percentil 26% global. Apesar de estar abaixo da média mundial, os resultados detalhados mostram bom desempenho em testes como Integer Math e Compression. O Monitor de Recursos indica que `chrome.exe` e `System` são alguns dos processos que mais utilizam a CPU.