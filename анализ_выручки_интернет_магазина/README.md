# Анализ выручки интернет-магазина


## Описание

Проведена приоритизация гипотез по фреймворкам ICE и RICE, а также осуществлен анализ результатов A/B-теста. 
Построены графики кумулятивной выручки, среднего чека, конверсии по группам, посчитана статистическая значимость различий конверсий и средних чеков по сырым и очищенным данным. На основании результатов анализа было принято решение о нецелесообразности проведения дальнейшего тестирования.

## Задача

Используя данные интернет-магазина приоритизировать гипотезы, произвести оценку результатов A/B-тестирования различными методами.

## Данные

В наличии были следующие данные о гипотезах:
- краткое описание гипотезы
- охват пользователей по 10-балльной шкале
- влияние на пользователей по 10-балльной шкале
- уверенность в гипотезе по 10-балльной шкале
- затраты ресурсов на проверку гипотезы по 10-балльной шкале

Данные о заказах:
- идентификатор заказа
- идентификатор пользователя, совершившего заказ
- дата, когда был совершён заказ
- выручка заказа
- группа A/B-теста, в которую попал заказ

Данные о пользователях и тестовых группах:
- дата
- группа A/B-теста
- количество пользователей в указанную дату в указанной группе A/B-теста

## Используемые библиотеки
*pandas, matplotlib, numpy, scipy*
