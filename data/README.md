# Данные проекта

## raw

- `resorts.json` — матрица признаков курортов; первая строка содержит названия полей.
- `prices_monthly.json` — цены по месяцам; первая строка содержит названия полей.
- `climate_monthly.json` — месячные климатические показатели.
- `rosstat_tourist_trips.csv` — выгрузка туристских поездок по регионам.
- `rosstat_tourist_nights.csv` — выгрузка ночёвок по регионам.
- `resort_open_data.json` — полный результат сбора открытых данных.

## processed

- `model_data.json` — итоговые признаки, нормированные баллы и контрольный рейтинг.
- `rosstat_enrichment.json` — дополнительные показатели Росстата и Roschart.

## reference

- `regional_tourism_sources.json` — список региональных источников и отметки о доступности данных.

## workbooks

- `Travel_Designer_Popularity_Prototype.xlsx` — контрольный расчёт рейтинга.
- `Travel_Designer_Resorts_and_Monthly_Prices.xlsx` — исходный список курортов и подготовленные цены.

Не исправляйте файлы из `raw` вручную. Очистку, замену типов и обработку пропусков выполняйте кодом.
