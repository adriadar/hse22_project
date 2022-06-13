# hse_project

Последовательности в геномах - хромосомы.

| Название | Название RefSeq | Кол-во аннотир. генов | Общая длина последовательностей | Кол-во последовательностей в геноме | Доля аннотир. генов | 
| -------- | --------------- | ----------------------------------- | ------------------------------- | --------------------- | ------------------- |
| Candida dubliniensis | GCF_000026945.1  | 6093 | 14618422 | 17924	| 0.623914 |
| Eremothecium gossypii  | GCF_000091025.4  | 5356 | 9119312  | 15479	| 0.804823 | 
| Candida albicans  | GCF_000182965.3  | 6263 | 14282666  | 18556	| 0.634822 |
| Eremothecium cymbalariae | GCF_000235365.1  | 4851 | 9669424 | 13866	 | 0.736149 | 
| Candida orthopsilosis | GCF_000315875.1  | 5782 | 12659401 | 17229	 | 0.675975 | 

| Название  | Название генов | Кол-во Z-ДНК >= 500 | Длина Z-ДНК >= 500   |
| --------- | -------- | ------------- | ----------- | 
| Candida dubliniensis| GCF_000026945.1  | 1064 | 11836 |
| Eremothecium gossypii  | GCF_000091025.4  | 5121 | 51148 |
| Candida albicans  | GCF_000182965.3  | 1100 | 12006 |
| Eremothecium cymbalariae | GCF_000235365.1  | 1127 | 11794 |
| Candida orthopsilosis | GCF_000315875.1  | 1134 | 11736 |

## Гистограмы

(если нарисовать на одном графике, то ничего не будет понятно, так как значения сильно отличаются)

![image](https://user-images.githubusercontent.com/58707354/173412268-768e4704-867b-4a0f-aef7-9c6963b9771f.png)
![image](https://user-images.githubusercontent.com/58707354/173412291-d37534b0-ffbd-4a57-b441-cf818a99f132.png)
![image](https://user-images.githubusercontent.com/58707354/173412320-f0b5ed99-3391-4988-b791-a5fe4d9f0825.png)
![image](https://user-images.githubusercontent.com/58707354/173412339-4923afcf-e0cc-46f1-abf7-861649d7f5e4.png)
![image](https://user-images.githubusercontent.com/58707354/173412361-5b9cbd5b-0107-4beb-87df-c4bfb4cf6ca8.png)



#### Ноутбуки:
[основной ноутбук (до кластеризации)](https://colab.research.google.com/drive/1-1bBT8vFovMzNzpgtjYohGVUZcXbdaRo?usp=sharing)

[ноутбук с кластеризацией](https://colab.research.google.com/drive/1_QqrvuLyPzKsh0asfE-lVIGLAtbUO5aR#scrollTo=x9TB8apN0WNA)

У меня получилось всего 6622 кластера. Кластеров, в которых 5 генов - 2923. У меня получился только один кластер, в котором есть Z-ДНК у всех 5 белков, один кластер, в котором есть Z-ДНК у 4 белков, 30 кластерjd, в котором есть Z-ДНК у 3 белков.
