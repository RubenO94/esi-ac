
# 📊 Comparação de Desempenho – Memória Principal (RAM)

---

## 🧠 Especificações Gerais

| Característica          | Ruben                          | Raul                          |
|-------------------------|--------------------------------|-------------------------------|
| Capacidade Total        | 16 GB DDR3                     | 16 GB DDR4                    |
| Velocidade              | 1333 MHz                       | 2400 MHz                      |
| Fator de forma          | DIMM                           | SODIMM (portátil)             |
| Canais usados           | 2 de 4                         | 2 de 2                        |

---

## 📈 Utilização Real – Task Manager

| Situação                | Ruben                          | Raul                          |
|-------------------------|--------------------------------|-------------------------------|
| Idle (em uso)           | 12,2 GB (~77%)                 | 5,8 GB (~36%)                 |
| Com apps abertas        | —                              | 7,6 GB (~47%)                 |
| Cache                   | 3,5 GB                         | 5,4 GB                        |
| Bloco Paginado          | 845 MB                         | 417 MB                        |

---

## 📊 Resource Monitor

| Métrica                | Ruben         | Raul         |
|------------------------|---------------|--------------|
| Hard Faults/sec        | 0             | 0            |
| Livre (Idle)           | ~3,4 GB       | ~2,5 GB      |
| Em Espera (Idle)       | ~6,0 GB       | ~5,6 GB      |

---

## 🧪 Benchmark – PassMark Memory Mark

| Métrica                  | Ruben           | Raul            |
|--------------------------|------------------|------------------|
| Memory Mark Score        | 1843             | 1409             |
| Percentil Global         | 14%              | 6%               |
| Read Cached              | 25.009 MB/s      | 15.717 MB/s      |
| Read Uncached            | 9.694 MB/s       | 10.619 MB/s      |
| Write                    | 6.473 MB/s       | 4.996 MB/s       |
| Latência                 | 52 ns            | 97 ns            |
| Threaded Read            | 15.977 MB/s      | 22.369 MB/s      |
| Database Ops             | 1.997 ops/s      | 1.541 ops/s      |

---

## 🔬 Teste de Estabilidade

| Ferramenta               | Ruben       | Raul             |
|--------------------------|-------------|------------------|
| Tipo de Teste            | MemTest86   | Windows Diagnostic |
| Ciclos concluídos        | 1           | 2                |
| Erros Detetados          | 0           | 0                |
| Páginas testadas         | ~3.5M        | ~3.8M             |

---

## ✅ Conclusão Comparativa

- O computador do **Ruben** apresenta **melhor desempenho em benchmarks**, especialmente em latência e leitura sequencial/cached, mesmo com DDR3 a 1333 MHz.
- O **Raul** tem uma RAM mais moderna (DDR4 a 2400 MHz) mas **não está otimizada em desempenho**, com latência mais alta e score inferior.
- Ambos os sistemas são **estáveis e funcionais**, mas o Ruben tem uma leve vantagem prática, enquanto o Raul ainda tem margem para otimização (dual-channel ativo, mas possível limitação por controlo térmico ou firmware).

