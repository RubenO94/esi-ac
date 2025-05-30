## 📊 Análise via Resource Monitor – Disco

Durante o período de monitorização, observou-se a atividade dos dois discos através do Monitor de Recursos do Windows.

### 🔍 Processos com atividade de disco significativa:
| Processo        | Leitura (B/s) | Escrita (B/s) | Total (B/s) | Tempo de Resposta (ms) |
|----------------|----------------|----------------|--------------|--------------------------|
| `Code.exe`     | 524.698        | 250.197        | 774.895      | 24                       |
| `System`       | 3.565          | 0              | 3.565        | 4                        |
| `svchost.exe`  | 630            | 0              | 630          | 20                       |
| `explorer.exe` | 68             | 0              | 68           | 210                      |

### 🧠 Observações:
- O processo **Code.exe (VS Code)** foi o mais ativo no disco, com ~775 KB/s de atividade.
- O tempo de resposta médio dos processos manteve-se **baixo (≤24 ms)**, exceto `explorer.exe`, que registou **210 ms** (pode indicar atraso pontual).
- O **uso geral do disco** estava bastante leve (~1% tempo de atividade máxima).

📁 Screenshot: `resmon_disk.png`
