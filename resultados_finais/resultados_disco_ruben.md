
# 💾 Avaliação do Desempenho – Memória Secundária (Discos)

---

## 📊 Monitorização via Task Manager

### Disco 0 (C:) – Samsung SSD 840 EVO 250GB
- Tipo: SSD
- Capacidade: 233 GB
- Tempo ativo: 3%
- Tempo de resposta médio: 1,1 ms
- Velocidade de escrita: 238 KB/s
- Velocidade de leitura: 0 KB/s
- Disco de sistema: Sim
- Ficheiro de paginação: Sim

📁 Screenshot: `disk-c.png`

### Disco 1 (D:) – ST2000DM001-1ER164
- Tipo: HDD
- Capacidade: 1,8 TB
- Tempo ativo: 0%
- Tempo de resposta médio: 0,3 ms
- Velocidade de escrita: 20,5 KB/s
- Velocidade de leitura: 0 KB/s
- Disco de sistema: Não
- Ficheiro de paginação: Não

📁 Screenshot: `disk-d.png`

---

## 📈 Monitorização via Resource Monitor

### Atividade de Disco:
| Processo       | Leitura (B/s) | Escrita (B/s) | Total (B/s) | Tempo de Resposta (ms) |
|----------------|----------------|----------------|--------------|--------------------------|
| Code.exe       | 524.698        | 250.197        | 774.895      | 24                       |
| explorer.exe   | 68             | 0              | 68           | 210                      |
| svchost.exe    | 630            | 0              | 630          | 20                       |
| System         | 3.565          | 0              | 3.565        | 4                        |

📁 Screenshot: `resmon_disk.png`

---

## 🧪 Verificação de Saúde – CrystalDiskInfo

### SSD (C:) – Samsung SSD 840 EVO 250GB
- Estado de Saúde: Saudável (64%)
- Temperatura: 42 ºC
- Total Host Writes: ~100.945 GB
- Horas ligadas: 18.962
- Número de ligações: 5.275
- Atributo relevante: Wear Leveling Count = 64

📁 Screenshot: `crystaldiskinfo_ssd.png`

### HDD (D:) – ST2000DM001-1ER164
- Estado de Saúde: Saudável (100%)
- Temperatura: 34 ºC
- Horas ligadas: 17.893
- Número de ligações: 5.112
- Atributo relevante: 0 setores realocados

📁 Screenshot: `crystaldiskinfo_hdd.png`

---

## 🚀 Benchmark – CrystalDiskMark

### SSD (C:) – Samsung SSD 840 EVO 250GB

| Tipo de Teste           | Leitura (MB/s) | Escrita (MB/s) |
|-------------------------|----------------|----------------|
| SEQ1M Q8T1              | 541,73         | 513,67         |
| SEQ1M Q1T1              | 502,42         | 486,56         |
| RND4K Q32T1             | 279,95         | 242,16         |
| RND4K Q1T1              | 35,38          | 88,79          |

📁 Screenshot: `crystaldiskmark_ssd.png`

### HDD (D:) – ST2000DM001-1ER164

| Tipo de Teste           | Leitura (MB/s) | Escrita (MB/s) |
|-------------------------|----------------|----------------|
| SEQ1M Q8T1              | 210,12         | 203,28         |
| SEQ1M Q1T1              | 205,45         | 207,70         |
| RND4K Q32T1             | 1,56           | 1,36           |
| RND4K Q1T1              | 0,63           | 1,24           |

📁 Screenshot: `crystaldiskmark_hdd.png`

---

✅ **Conclusão**: Ambos os discos encontram-se em bom estado de saúde. O SSD apresenta excelente desempenho e é apropriado para sistema operativo e aplicações. O HDD, embora saudável, apresenta velocidades muito baixas em leitura/escrita aleatória, sendo mais indicado para armazenamento de dados de grande volume.
