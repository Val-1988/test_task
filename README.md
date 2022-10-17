# test_task


Задание:
Сайт 1: h)ps://oriencoop.cl/sucursales.htm
Сайт 2: h)ps://som1.ru/shops/
Сайт 3: h)ps://naturasiberica.ru/our-shops/
Задача:
Написать 3 скрипта, которые соберут с сайта по всем городам адрес (город, улица,
номер дома и т.п.), координаты, время работы (разделённое по дням) и телефоны
(общий и дополнительные, если указаны).
Описание:
Скрипт должен сформировать json файл, в котором будет храниться массив
объектов вида, указанного в примерах. Внимание к типам данных, кавычки,
запятые и скобки расставлены в примере не просто так. Исключить использование
selenium.
формат json файла:
для сайта 1:
[
{
"address": "Bernardo O Higgins 479 - San Fernando",
"latlon": [-70.98583, -34.589468],
"name": "Oriencoop",
"phones": [ "72201048", "600 200 0015", "+56712207838"]
"working_hours": ["mon-thu 8:50 - 14:10 15:00-17:10", "fri 8:50 - 14:10
15:00-17:10"]
},
...
]
для сайта 2
[
{
"address": "г. Нижний Тагил, Свердловское шоссе, 31",
"latlon": [57.919399476044, 59.951100761902],
"name": "СОМ на Красноармейской",
"phones": [ "88002500900", "84957857655", "79826903887"],
"working_hours": ["пн – вс 08:00 – 21:00"]
},
...
]
для сайта 3
[
{
"address": "Москва, Маросейка д. 4/2, строение 1,
"latlon": [62.031799, 129.754762] (тут со "звёздочкой"),
"name": "Natura Siberica",
"phones": [ "74992719642"],
"working_hours": ["пн-вс 10:00-22:00" ]
},
...]
