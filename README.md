# Рейтинг горнолыжных курортов России — Travel Designer

Проект представляет собой воспроизводимый расчет рейтинга 32 горнолыжных курортов России на основе открытых данных. 
Итоговый результат — аналитический дашборд в Yandex DataLens, показывающий потенциал курортов, их сильные и слабые стороны, а также качество исходных данных.

## 🚀 Ссылки
* **Дашборд в DataLens:** ([https://datalens.ru/dld2owwpi24ww-reyting-gornolyzhnyh-kurortov-rossii](https://datalens.ru/dld2owwpi24ww-reyting-gornolyzhnyh-kurortov-rossii?_share_link=org)
* **Техническое задание:** `docs/Travel_Designer_TZ_Resort_Ranking.docx`

## 📁 Структура проекта
* `data/raw/` — исходные файлы (выгрузки ЕМИСС, Росстат, OurAirports) и ответы API (OSM, Open Meteo). **Не редактируются вручную.**
* `data/processed/` — очищенные и подготовленные таблицы (`model_data.json`), а также итоговые выгрузки для DataLens (`rating_result.csv`, `rating_full.csv` и др.).
* `src/` — скрипты для сбора данных, очистки, агрегации и расчета баллов.
* `notebooks/` — исследовательские ноутбуки (аудит данных, проверка формул).
* `README.md` — инструкция по запуску и описание проекта.

## ⚙️ Как воспроизвести расчет

Для работы требуется **Python 3.10+** и установленные библиотеки:
```bash
pip install -r requirements.txt
