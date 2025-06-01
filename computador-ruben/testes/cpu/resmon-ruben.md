## 📈 Monitorização Detalhada – Resource Monitor (CPU)

Durante a análise com o **Resource Monitor**, foram identificados os seguintes processos com maior utilização do processador:

### 🧠 Processos mais ativos:
| Processo                  | Threads | Utilização Média (%) |
|---------------------------|---------|-----------------------|
| LeagueClientUxRender.exe | 20      | 7,21%                 |
| League of Legends         | 56      | 2,67%                 |
| perfmon.exe               | 10      | 2,03%                 |
| WMI Provider Host         | 21      | 1,84%                 |
| Sistema                   | 12      | 0,74%                 |
| TranslucentTB             | 13      | 0,73%                 |

📁 Screenshot: `cpu_resmon.png`

### 📌 Observações:
- A maior parte da carga está a ser gerada por aplicações gráficas e o jogo **League of Legends**.
- A utilização global dos núcleos é equilibrada, com atividade visível em todos os gráficos de CPU.
- Nenhum processo isolado causou uso anormal ou travamentos, indicando um bom balanceamento de carga.
