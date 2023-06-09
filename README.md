# indiv_project_2023
## Информация о гене:
Ген: ERBB4 - мембранный белок из семейства рецептора эпидермального фактора роста EGFR/ErbB рецепторных тирозиновых протеинкиназ, кодируется геном человека ERBB4.

Эпигенетическая функция: histone modification cofactor

Статьи: 
[Nuclear ErbB4 signaling through H3K9me3 is antagonized by EGFR-activated c-Src](https://pubmed.ncbi.nlm.nih.gov/23230144/)
В этой статье было показано, что уровень H3K9me3 в клетках увеличивался  при стимуляции рецепторов ErbB4 с помощью NRG-1 ( за счет внутриклеточного домена).

[Role for tyrosine phosphorylation of SUV39H1 histone methyltransferase in enhanced trimethylation of histone H3K9 via neuregulin-1/ErbB4 nuclear signaling](https://pubmed.ncbi.nlm.nih.gov/30833073/)
В этой статье было показано, что гистоновая метилтрансфераза H3K9 SUV39H1 связывается с NRG-1/ErbB4, что приводит к возникновению H3K9me3.

## Выравнивание гистонов:
| Гистон      | Выравнивание | Комментарий |
| ------------- |------------------| -----|
| H2A     | ![image_2023-06-06_20-25-42](https://github.com/sonishko/indiv_project_2023/assets/99287058/5b3a801f-fe2b-4fa3-b580-0a11cd4885ea)| Наблюдается полиморфизм генов, последовательности отличаются, но это не слишком критично.|
|   H2B   | ![image_2023-06-06_20-27-29](https://github.com/sonishko/indiv_project_2023/assets/99287058/1b6977d6-b981-42da-ba29-a0d1bd848850) |  Наблюдается полиморфизм генов, последовательности отличаются, но это не слишком критично. |
| H3 | ![image_2023-06-06_20-26-56](https://github.com/sonishko/indiv_project_2023/assets/99287058/dcee9eea-668f-43d1-bf9e-03a611383eb4) | Различия наблюдаются лишь в последовтельности двух кодонов в двух последних последовательностях, что говорит о том, что гены являются копиями|
| H4 | ![image_2023-06-06_20-27-57](https://github.com/sonishko/indiv_project_2023/assets/99287058/bb826314-5bdf-4bb8-991d-d5f9619688fb)| Между последовательностями практически нет различий (немного наблюдается полиформизм), но в целом гены являются копиями.|

## Таблица e-value и -log(e-value)
<img width="916" alt="Снимок экрана 2023-06-06 в 20 55 01" src="https://github.com/sonishko/indiv_project_2023/assets/99287058/51b7a439-72ac-469a-b2f9-40d47155b646">

## Тепловая карта
<img width="973" alt="Снимок экрана 2023-06-06 в 21 01 37" src="https://github.com/sonishko/indiv_project_2023/assets/99287058/0b5285ef-a7bd-42cd-8668-bbef8464938e">

Полученная тепловая карта говорит о том, что белок ERBB4 появился впервые у эукариот, но более четко он детектируется у позвоночных организмов. Таким образом, этот белок является достаточно эволюционно старым.

## Код и ресурсы.

1. Выравнивание гистонов проводила в приложении MegaX с помощью алгоритма MUSCLE
2. Выравнивания последовательностей на сервере: blastp -query protein.fasta -db /mnt/storage/project_2023/proteomes/proteome.faa -out proteome.blast -outfmt 7
3. Тепловую карту строила с помощью [python](https://colab.research.google.com/drive/1TPSTTm8t5eP79WOl21RbNzdvcX5CMt5f?usp=sharing)
