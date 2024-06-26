# Исследование объявлений о продаже квартир

## Описание проекта

Тредуется изучить архив объявлений о продаже квартир в Санкт-Петербурге и соседних населённых пунктов за несколько лет, чтобы определить рыночную стоимость объектов недвижимости.

Предоставлены данные двух типов: от пользователей и автоматические, полученные на основе картографических данных.

## Навыки и инструменты

- python
- pandas
- matplotlib
- seaborn

## Общий вывод

В ходе исследования была выполнена предобработка данных: обработка пропусков, дубликатов и аномальных значений, заменены типы данных. И проведен ИАД: проанализированы основные параметры объектов.

Профиль стандартной квартиры на продажу в районе СПБ и ЛО:

* площадь квартиры от 40 до 69 м² (из них жилая примерно 30 м², площадь кухни - 9 м²), с высотой потолков 2,6 м
* двух- или трехкомнатная квартира, расположенная ниже 5 этажа в 5 этажном доме не в новостройке
* расположение на окраинной части Питера (в его пределах, но далеко от центра)
* достаточно далеко от аэропорта, в пешей доступности есть парк
* цена около 5 млн рублей

Что удалось выяснить в результате исследования:

1. Скорость продажи квартир - примерно 3 месяца.

2. Главный фактор, влияющий на стоимость квартиры - общая площадь. Цена также зависит от этажа, на котором расположена квартира - первый этаж самый дешевый. Основные дни, когда велись продажи это будни, особено во вторник квартиры стоили дороже, а в воскресенье наоборот дешевле. Пик продаж приходится на апрель, а спад на июль.

3. Самая высокая стоимость одного квадратного метра в Санкт-Петербурге, самая низкая - в Выборге.

4. Цена на квартиры начинают снижаться за 6 км от центра.
