# Лабораторные работы по курсу Мультимедиа

Выполнил: Белоносов К.А.
Группа: М8О-408Б-21

## Датасеты

- Классификация: Качество вина в зависимости от химического состава - https://www.kaggle.com/datasets/shree1992/housedata

- Регрессия: Оценка стоимости жилья - https://www.kaggle.com/datasets/shree1992/housedata

## Лабораторные работы

1. [Проведение исследований с алгоритмом KNN](/AiDa.ipynb)
2. [Проведение исследований с логистической и линейной регрессией](/AiDa2.ipynb)
3. [Проведение исследований с решающим деревом](/AiDa3.ipynb)
4. [Проведение исследований со случайным лесом](/AiDa4.ipynb)
5. [Проведение исследований с градиентным бустингом](/AiDa5.ipynb)

## Итоги

- Классификация

| Алгоритм            | Baseline | Улучшенный бейзлайн | Имплементация | Улучшенный бейзлайн и имплементация |
|---------------------|----------|---------------------|---------------|-------------------------------------|
| KNN                 |Acc: 0.5939 F1: 0.5866|Acc: 0.6375 F1: 0.6224|Acc: 0.5983 F1: 0.5983|Acc: 0.5983 F1: 0.5800|
| Линейные модели     |Acc: 0.5590 F1: 0.5337|Acc: 0.4868 F1: 0.5416|Acc: 0.5458 F1: 0.4806|Acc: 0.4810 F1: 0.5324|
| Решающее дерево     |Acc: 0.5459 F1: 0.5416|Acc: 0.5977 F1: 0.5976|Acc: 0.5371 F1: 0.5248|Acc: 0.5714 F1: 0.5612|
| Случайный лес       |Acc: 0.6900 F1: 0.6801|Acc: 0.6900 F1: 0.6776|Acc: 0.6157 F1: 0.6018|Acc: 0.6201 F1: 0.5991|
| Градиентный бустинг |Acc: 0.6332 F1: 0.6255|Acc: 0.6594 F1: 0.6543|Acc: 0.5284 F1: 0.4830|Acc: 0.6026 F1: 0.5585|

- Регрессия

| Алгоритм            | Baseline | Улучшенный бейзлайн | Имплементация | Улучшенный бейзлайн и имплементация |
|---------------------|----------|---------------------|---------------|-------------------------------------|
| KNN                 |RMSE: 319024.15 $R^2$: 0.2929|RMSE: 113414.29 $R^2$: 0.6902|RMSE: 769682.09 $R^2$: 0.0735|RMSE: 167598.61 $R^2$: 0.3237|
| Линейные модели     |RMSE: 749683.74 $R^2$: 0.1210|RMSE: 211577.87 $R^2$: 0.5442|RMSE: 751253.83 $R^2$: 0.1173|RMSE: 240692.48 $R^2$: 0.4101|
| Решающее дерево     |RMSE: 777331.99 $R^2$: 0.0550|RMSE: 238610.66 $R^2$: 0.4482|RMSE: 761764.25 $R^2$: 0.0925|RMSE: 262317.23 $R^2$: 0.3332|
| Случайный лес       |RMSE: 216876.39 $R^2$: 0.6460|RMSE: 112026.73 $R^2$: 0.7198|RMSE: 262082.23 $R^2$: 0.4830|RMSE: 139889.71 $R^2$: 0.5631|
| Градиентный бустинг |RMSE: 242692.34 $R^2$: 0.5567|RMSE: 117536.68 $R^2$: 0.6916|RMSE: 257931.13 $R^2$: 0.4993|RMSE: 148392.93 $R^2$: 0.5084|

### Лучший в задаче классификации

- Accuracy:
  1. Значение: 0.6900
  2. Алгоритм: Случайный лес
  3. Версия: Улучшенный baseline
- F1:
  1. Значение: 0.6801
  2. Алгоритм: Случайный лес
  3. Версия: Обычный baseline

### Лучший в задаче регрессии

- RMSE:
  1. Значение: 112026.73
  2. Алгоритм: Случайный лес
  3. Версия: Улучшенный baseline
- $R^2$:
  1. Значение: 0.7198
  2. Алгоритм: Случайный лес
  3. Версия:  Улучшенный baseline
