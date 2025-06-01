# 🧠 Avaliação da Memória Principal (RAM) – Computador Ruben

---

## 📊 Task Manager – Uso de Memória

- Capacidade total: 16,0 GB DDR3
- Utilização atual: 12,2 GB (77%)
- Disponível: 3,7 GB
- Velocidade: 1333 MHz
- Formato: DIMM
- Ranhuras utilizadas: 2 de 4
- Em cache: 3,5 GB
- Alocada: 20,7 GB de 24,9 GB
- Bloco paginado: 845 MB
- Bloco não paginado: 503 MB
- Reservada ao hardware: 51,4 MB

📁 Screenshot: `task_manager.png`

---

## 📈 Resource Monitor – Detalhes da Memória

- Memória Física Total: 16384 MB (≈16.0 GB)
- Reservada ao Hardware: 52 MB
- Em Utilização: 9816 MB
- Modificado: 97 MB
- Em Espera: 5968 MB
- Livre: 451 MB
- Disponível: 6419 MB
- Em cache: 6065 MB
- Hard Faults/sec: 0 (indica que o sistema não está a recorrer ao disco por falta de RAM neste momento)

- Principais processos a consumir RAM:
  - `Discord.exe`
  - `brave.exe` (navegador)
  - `MsMpEng.exe` (Windows Defender)
  - `Code.exe` (Visual Studio Code)
  - `SteamWebHelper.exe`
  - `RiotClientServices.exe`
  - `SteelSeriesEngine.exe` (background gaming/periféricos)

📁 Screenshot: `resmon.png`

---

## 🛠 Diagnóstico – MemTest86

O teste de estabilidade da memória RAM foi realizado utilizando o MemTest86 v11.3 Free Edition, corrido através de uma pen USB bootável. Foi executado 1 ciclo completo de testes de leitura e escrita sobre a totalidade da memória disponível.

- Passes concluídos: 1 (de 4 possíveis)
- Erros encontrados: 0 (Total errors: 0, ECC errors: 0)
- Duração do teste: ~28 minutos
- Configuração testada:
  - Memória: 15.9 GB DDR3
  - Frequência: 1334 MT/s
  - Dual Channel (x2 Channel)
  - Módulo: Corsair CMD16GX3M2A2400C11
  - CPU: Intel Core i7-4790K @ 4.00 GHz

A ausência de erros confirma que os módulos de memória apresentam estabilidade e funcionamento adequado sob carga completa.

📁 Screenshots: `memetest86_test_begin.jpg`, `memetest86_test_done.jpg`

---

## 🧪 Benchmark – PassMark Memory Mark

- Memory Mark Score: 1843
- Percentil Global: 14% (abaixo da média mundial)
- World Average: 2725
- World Maximum: 6378

#### 🔍 Resultados por categoria:
- Memory Read Cached: 25.009 MB/s
- Memory Read Uncached: 9.694 MB/s
- Memory Write: 6.473 MB/s
- Memory Latency: 52 ns
- Available RAM: 6.241 MB
- Memory Threaded: 15.977 MB/s
- Database Operations: 1.997 ops/s

📁 Screenshot: `passmark.png`

---

✅ **Conclusão**:
A memória RAM do computador do Ruben (16 GB DDR3 a 1333 MHz) demonstra estabilidade e funcionamento adequado, conforme evidenciado pela ausência de erros no teste MemTest86. Embora o benchmark PassMark Memory Mark mostre uma pontuação de 1843, colocando-o abaixo da média mundial no percentil 14%, os resultados detalhados de leitura, escrita e latência indicam um desempenho sólido. O Resource Monitor e Task Manager revelam o uso da memória sob diferentes cargas, com processos como Discord e Brave a serem os principais consumidores de RAM.