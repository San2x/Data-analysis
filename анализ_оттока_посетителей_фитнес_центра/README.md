# Анализ оттока посетителей фитнес-центра


## Описание

На основе алгоритмов машинного обучения построена модель прогноза вероятности оттока для каждого клиента (на уровне следующего месяца),
сформированы типичные портреты пользователей: выделены наиболее яркие группы, охарактеризованы их основные свойства,
проанализированы основные признаки, наиболее сильно влияющие на отток.

## Задача

На основе данных о посетителях сети фитнес-центров спрогнозировать вероятность оттока для каждого клиента в следующем месяце, сформировать с помощью кластеризации портреты пользователей.

## Данные

В наличии были следующие данные о посетителях и их активности:
- пол
- проживание или работа в районе, где находится фитнес-центр
- сотрудник компании-партнёра клуба
- факт первоначальной записи в рамках акции «приведи друга»
- наличие контактного телефона
- возраст
- время с момента первого обращения в фитнес-центр 
- длительность текущего действующего абонемента 
- срок до окончания текущего действующего абонемента
- факт посещения групповых занятий
- средняя частота посещений в неделю за все время с начала действия абонемента
- средняя частота посещений в неделю за предыдущий месяц
- суммарная выручка от других услуг фитнес-центра
- факт оттока в текущем месяце
 
## Используемые библиотеки
*pandas, matplotlib, seaborn, scipy, scikit-learn*
