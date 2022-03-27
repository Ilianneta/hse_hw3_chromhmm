# hse_hw3_chromhmm

Клеточная линия HepG2

Колаб: https://colab.research.google.com/drive/1WASMwwlSKhyF7fo8O2AYEqjVzF6Y2vuW?usp=sharing

![Снимок экрана (96)](https://user-images.githubusercontent.com/56909634/160294758-6fc74dad-7007-4325-8526-4b1b8b05ac51.png)

![emissions_10](https://user-images.githubusercontent.com/56909634/160294819-9a7e4fec-bdfc-4805-9263-2c2caf3e12c3.png)
![HepG2_10_overlap](https://user-images.githubusercontent.com/56909634/160294825-43e61173-2724-4d03-9ed5-0bf84d3fea17.png)
![transitions_10](https://user-images.githubusercontent.com/56909634/160294828-07296d03-3a24-4b3d-8e34-6b5ca6fd2168.png)
![HepG2_10_RefSeqTES_neighborhood](https://user-images.githubusercontent.com/56909634/160294830-f35af110-459e-4b46-a598-ef286f2c4de3.png)
![HepG2_10_RefSeqTSS_neighborhood](https://user-images.githubusercontent.com/56909634/160294833-45e344d8-caab-4109-8a51-e2880b207ce6.png)

| Состояние | Гист. модификации                  | С чем ассоциировано | Эпигенетический тип
| ------------- |:------------------:| -----:|
| 1         | H3k27me3                           | RefSeqGene, RefSeqTES | Weak transcribed |
| 2         | H3k79me2                           | RefSeqGene | Weak transcribed |
| 3         | H3k79me2, H3k04me1                 | RefSeqGene | Weak transcribed |
| 4         | H3k04me1                           | RefSeqTES (слабо), RefSeqGene (еще слабее) | Weak enhancer |
| 5         | H3k4me2, H3k9ac, H3k27ac, H3k04me1 | RefSeqTES, RefSeqGene (слабо)  | Weak enhancer |
| 6         | H3k4me3, H3k4me2, H3k9ac, H3k27ac  | CpG-островки, RefSeqExon, RefSeqTES (слабее), RefSeqTSS | Active Promoter |
| 7         | H3k4me3, H3k4me2, H3k04me1         | CpG-островки (слабо), RefSeqTES (слабо) | Weak Promoter |
| 8         | H3k27me3                           | Ядерная ламина | Heterochromatin |
| 9         | -                                  | Ядерная ламина | Heterochromatin |
| 10        | H3k09me3                           | Ядерная ламина | Heterochromatin |
