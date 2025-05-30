
# 💾 Comparação de Desempenho – Memória Secundária (Discos)

---

## 📦 Especificações Gerais

| Característica          | Ruben (SSD + HDD)            | Raul (Disco único SATA)       |
|-------------------------|------------------------------|-------------------------------|
| SSD                    | Samsung SSD 840 EVO 250GB    | Não especificado (SATA)       |
| HDD                    | ST2000DM001-1ER164 (2 TB)    | —                             |
| Interface              | SATA/600                     | SATA                          |
| Temperatura média      | 34–42 ºC                     | ~35 ºC                        |
| Estado SMART           | Saudável (SSD: 64%)          | Saudável                      |

---

## 📈 Monitorização – Task Manager

| Situação                | Ruben                         | Raul                          |
|-------------------------|-------------------------------|-------------------------------|
| Idle                    | SSD ativo a 3%                | Disco inativo (~0%)           |
| Carga                  | HDD leitura leve              | Uso aumentou durante instalação |

---

## 📊 Resource Monitor

- **Ruben**:
  - Processo mais ativo: `Code.exe` (~775 KB/s)
  - Tempos de resposta baixos
- **Raul**:
  - Utilização leve durante idle
  - Nenhuma fila de leitura/escrita significativa

---

## 🛠 Estado de Saúde – CrystalDiskInfo

| Métrica                        | Ruben SSD               | Raul Disco                  |
|-------------------------------|--------------------------|-----------------------------|
| Estado                        | Saudável (64%)          | Saudável                   |
| Horas de uso                  | ~18.900 h               | Não especificado            |
| Setores realocados            | 0                        | 0                           |
| Wear Level Count              | 64                       | —                           |

---

## 🚀 Benchmark – CrystalDiskMark

| Teste                 | Ruben SSD     | Raul Disco (SATA) |
|----------------------|---------------|-------------------|
| Leitura SEQ1M Q8T1   | 541 MB/s      | ~150–200 MB/s (*) |
| Escrita SEQ1M Q8T1   | 513 MB/s      | ~150–200 MB/s (*) |
| Leitura 4K Q1T1      | 35 MB/s       | < 1 MB/s          |
| Escrita 4K Q1T1      | 88 MB/s       | ~1 MB/s           |

(*) Estimado com base em disco SATA típico, sem valores extraídos diretamente.

---

## ✅ Conclusão Comparativa

- O **Ruben**, com SSD e HDD, tem vantagem significativa na velocidade e resposta do sistema, especialmente em leitura aleatória (fundamental para SO e apps).
- O **Raul** utiliza um disco único SATA com bom estado, mas performance inferior, especialmente em operações aleatórias.
- Para tarefas com multitarefa e abertura rápida de ficheiros, o sistema do Ruben tem vantagem prática clara. O sistema do Raul continua funcional, mas poderia beneficiar de um upgrade para SSD.
