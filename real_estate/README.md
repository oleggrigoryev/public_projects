# Исследование рынка недвижимости

[Файл ipynb](https://github.com/oleggrigoryev/public_projects/blob/main/real_estate/notebook_project_RealEstateSpb_oleg_grigoryev.ipynb)

## Описание проекта

На основе данных сервиса Яндекс.Недвижимость с архивом объявлений о продаже квартир в Санкт-Петербурге и соседних населённых пунктах за несколько лет научиться определять рыночную стоимость объектов недвижимости и установить влияющие параметры.



## Стек

- _python_
- _pandas_
- _numpy_
- _plotly_
- _seaborn_
- _matplotlib_
- _data visualization_ 📊

## 

## Общий вывод

Я предобработал данные и проверил их реалистичность, избавился от пропущенных значений и дубликатов. На обработанных данных распределения выглядят нормально, хотя есть экстремально высокие значения в кол-ве комнат, высоте потолков и, соответственно, стоимости квартир.
Стало ясно, что данные были выгружены довольно давно, пришлось это учитывать при анализе времени размещения.
Я нашёл наиболее дорогие территории — Санкт-Петербург и Зеленогорск — и выяснил, что предложения в центральных районах значительно отличаются по многим параметрам от всей выборки. Они дороже, а квартиры просторнее.