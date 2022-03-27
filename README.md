# hse_hw3_chromhmm

## [Google Colab](https://colab.research.google.com/drive/1KsgIrD3Rdr47IQiBGiGNU5J3NEbHM8pG?usp=sharing)

## Table of histone labels and corresponding files

Like in previous hometask, a HepG2 cell line was taken.

| histone label | filename |
|---|---|
| Ctcf | HepG2_Ctcf.bam |
| Ezh239875 | HepG2_Ezh.bam |
| H2az | HepG2_H2az.bam |
| H3k04me1 | HepG2_H3k04me1.bam |
| H3k4me2 | HepG2_H3k4me2.bam |
| H3k4me3 | HepG2_H3k4me3.bam |
| H3k9ac | HepG2_H3k9ac.bam |
| H3k27ac | HepG2_H3k27ac.bam |
| H3k36me3 | HepG2_H3k36me3.bam |
| H3k79me2 | HepG2_H3k79me2.bam |

## Pictures from ChromHmm LearnModel output

![image](pics/HepG2_10_RefSeqTES_neighborhood.png)
![image](pics/HepG2_10_RefSeqTSS_neighborhood.png)
![image](pics/HepG2_10_overlap.png)
![image](pics/emissions_10.png)
![image](pics/transitions_10.png)

## Genome browser

![image](https://user-images.githubusercontent.com/86663451/160263260-f2f8f4c3-a114-4e4e-b05a-a5d516320b4f.png)

![image](https://user-images.githubusercontent.com/86663451/160263281-ea60cd66-a077-4df4-986e-dde642de59e8.png)

![image](https://user-images.githubusercontent.com/86663451/160263372-d6b7aee1-1600-4efe-9a1c-e671745c5e80.png)

![image](https://user-images.githubusercontent.com/86663451/160297305-672c806c-48a5-43f6-8617-9acf172993bc.png)

| Epigenetic type number and color | Given appellation | Mark | Features | 
| --- | --- | --- | --- | 
| 1 синий | Taxon | H3k36m3 | Не очень сильные сигналы, где-то до 20 |
| 2 голубой | Transcriptional | H3k79m2 | Зашкаливающие пики, такое ощущение, что выходят за 50 единиц | 
| 3 аквамарин | Taxon |  H3k4m1, H3k4m2, H3k49m2 | На H3k79m2 сильный сигнал, на H3k4m1/2 держится в средних границах | 
| 4 фиолетовый | Enhancer | H3k4m1 | Сильный сигнал на H3k4m1 | 
| 5 светло-зелёный | Promoter | H3k4m1 | Сильный плотный сигнал, проявляется ещё на H3k4m2 и H3k27ac |
| 6 тёмно-зелёный | Promoter | H3k79m2 | Сигнал сильный, причём много где. Отмечается на H3k4m2, H3k4m3 и на H3k9ac |
| 7 красный | Promoter | H3k4me2 | Сильный пик, ближе к 40 | 
| 8 горчичный | Repressed | Ezh2 | На графике пики выше, чем для 9. Ближе к концу сигналы самые сильные | 
| 9 жёлтый | Heterochromatin | H2az, Ezh2 | Много пиков малой и средней высоты на соответствующем графике сигнала, но на H2az проявляется отчётливее. Может попадать на хромосому | 
| 10 лиловый | Insulator | Ctcf | Очень высокий пик (в районе 50) на графике |

## Bonus task

![image](https://user-images.githubusercontent.com/86663451/160301178-2e8d241e-2a6b-40a4-b152-03bc96bb8c17.png)

![image](https://user-images.githubusercontent.com/86663451/160301235-c4b90c50-7fdf-43c4-9c00-39acf2fd6fc6.png)

