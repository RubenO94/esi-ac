
## 🧬 Metodologia – Memória Principal (RAM)

Para a avaliação do desempenho da memória principal (RAM), foram selecionadas ferramentas fiáveis e amplamente recomendadas no tutorial da unidade curricular. Estas permitem observar o uso da RAM em tempo real, testar a sua estabilidade e medir a sua performance em operações essenciais.

- **Task Manager**: Utilizado para observar a utilização total da RAM, frequência (MHz), número de slots ocupados, formato e canais. Permitiu também observar a variação de uso com diferentes aplicações em execução.
- **Resource Monitor (resmon)**: Complementar ao Task Manager, permitiu analisar detalhes como a quantidade de memória física em uso, cache, livre, e principalmente os *Hard Faults/s*, que indicam a utilização do disco por falta de RAM.
- **MemTest86**: Utilizado em ambiente de boot (fora do Windows), permitiu testar a estabilidade da RAM de forma completa e identificar possíveis erros físicos nos módulos.
- **PassMark PerformanceTest**: Através do teste Memory Mark, permitiu avaliar a latência da memória, largura de banda e operações de leitura, escrita e cópia, fornecendo uma pontuação global e permitindo comparação com outros sistemas semelhantes.

---

## 💾 Metodologia – Memória Secundária (Disco)

Com base no tutorial oficial, foram selecionadas ferramentas para avaliar a saúde, utilização e velocidade dos discos (SSD e HDD) utilizados. Estas ferramentas permitiram uma análise completa da performance e do estado dos dispositivos.

- **Task Manager**: Usado para monitorizar a atividade do disco em tempo real, incluindo percentagem de utilização, velocidade de leitura/escrita e tempo de resposta durante operações comuns.
- **Resource Monitor (resmon)**: Permitindo uma análise por processo, ajudou a identificar quais aplicações causavam maior carga no disco e permitiu observar os tempos de resposta por operação.
- **CrystalDiskInfo**: Ferramenta dedicada à leitura de atributos SMART dos discos, útil para verificar o estado de saúde ("Saudável", "Aviso", etc.), temperatura e erros associados ao dispositivo.
- **CrystalDiskMark**: Ferramenta de benchmarking que mediu a velocidade de leitura e escrita sequencial (Seq Q32T1) e aleatória (4K Q32T1), dados importantes para compreender o desempenho em tarefas reais.
