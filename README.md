# customers-purchases-e-commerce
## Техническое задание:

Необходимо проанализировать совершенные покупки и ответить на следующие вопросы:

1. Сколько пользователей, которые совершили покупку только один раз?
2. Сколько заказов в месяц в среднем не доставляется по разным причинам (вывести детализацию по причинам)?
3. По каждому товару определить, в какой день недели товар чаще всего покупается.
4. Сколько у каждого из пользователей в среднем покупок в неделю (по месяцам)? Не стоит забывать, что внутри месяца может быть не целое количество недель.
   Например, в ноябре 2021 года 4,28 недели. И внутри метрики это нужно учесть.
6. Выполнить когортный анализ пользователей. В период с января по декабрь выявить когорту с самым высоким retention на 3-й месяц.
7. Построить RFM-сегментацию пользователей, чтобы качественно оценить аудиторию. В кластеризации можно выбрать следующие метрики:
   R - время от последней покупки пользователя до текущей даты,
   F - суммарное количество покупок у пользователя за всё время,
   M - сумма покупок за всё время. Подробно описать, как были созданы кластеры.
   Для каждого RFM-сегмента построить границы метрик recency, frequency и monetary для интерпретации этих кластеров. Пример такого описания:
   RFM-сегмент 132 (recency=1, frequency=3, monetary=2) имеет границы метрик recency от 130 до 500 дней, frequency от 2 до 5 заказов в неделю,
   monetary от 1780 до 3560 рублей в неделю.
