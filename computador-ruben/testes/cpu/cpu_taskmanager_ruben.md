## 🧠 Monitorização de CPU – Task Manager

### 🔹 Cenário 1: Idle (Sistema inativo)

- **Utilização média**: 15%
- **Frequência**: 4,30 GHz
- **Processos ativos**: 200
- **Threads**: 2.682
- **Temperatura da GPU**: 52 ºC

📁 Screenshot: `cpu_idle.png`

---

### 🔹 Cenário 2: Carga Leve (Browser, apps leves abertas)

- **Utilização média**: 54%
- **Frequência**: 4,19 GHz
- **Processos ativos**: 243
- **Threads**: 3.568
- **Temperatura da GPU**: 57 ºC

📁 Screenshot: `cpu_leve.png`

---

### 🔹 Cenário 3: Carga Alta (Simulação ou stress)

- **Utilização média**: 88%
- **Frequência**: 4,18 GHz
- **Processos ativos**: 280
- **Threads**: 4.491
- **Temperatura da GPU**: 59 ºC

📁 Screenshot: `cpu_pesado.png`

---

### 🔍 Observações:

- O processador **Intel Core i7-4790K @ 4.00GHz** manteve frequência estável acima da base mesmo sob carga.
- Utilização sobe proporcionalmente com o número de processos e carga.
- Sem sinais de throttling ou queda de performance.
