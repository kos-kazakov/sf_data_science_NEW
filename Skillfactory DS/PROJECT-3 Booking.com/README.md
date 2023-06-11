# [PROJECT-1. Анализ резюме из HeadHunter](https://github.com/kos-kazakov/sf_data_science/tree/main/Skillfactory%20DS/PROJECT-1)

## Оглавление
* [1. Описание проекта](https://github.com/kos-kazakov/sf_data_science/blob/main/Skillfactory%20DS/PROJECT-1/README.md#Описание-проекта)
* [2. Какой кейс решаем?](https://github.com/kos-kazakov/sf_data_science/blob/main/Skillfactory%20DS/PROJECT-1/README.md#Исходные-данные)
* [3. Этапы проекта](https://github.com/kos-kazakov/sf_data_science/blob/main/Skillfactory%20DS/PROJECT-1/README.md#Этапы-проекта)
* [4. Краткая информация о данных](https://github.com/kos-kazakov/sf_data_science/blob/main/Skillfactory%20DS/PROJECT-1/README.md#Требования-к-оформлению-решения)
* [4. Результаты](https://github.com/kos-kazakov/sf_data_science/blob/main/Skillfactory%20DS/PROJECT-1/README.md#Результаты)

## Описание проекта
 Предсказание оценки отеля клиентом на основе полученного отзыва, данных об отеле и клиенте.

## Какой кейс решаем?
Представьте, что вы работаете дата-сайентистом в компании Booking. Одна из проблем компании — это нечестные отели, которые накручивают себе рейтинг. Одним из способов обнаружения таких отелей является построение модели, которая предсказывает рейтинг отеля. Если предсказания модели сильно отличаются от фактического результата, то, возможно, отель ведёт себя нечестно, и его стоит проверить.

### Условия
- Участие в соревновании на Kaggle (https://www.kaggle.com/competitions/sf-booking/).
- Использование Random Forest Regressor с - фиксированными параметрами.
- Способы улучшения метрики - очистка и разведывательный анализ данных: создание, преобразование и отбор признаков.

### Метрика качества
Качество модели - MAPE: Mean absolute percentage error

### Критерии оценки проекта (0-3 балла за каждый пункт)
- Качество кода (соблюдение стандартов оформления PEP-8, комментирование кода, README к проекту). Оформление проекта на GitHub, GitLab, Kaggle.
- Очистка данных.
- Исследование данных (качество визуализации, наличие идей, гипотез, комментариев).
- Генерация признаков.
- Отбор признаков.
- Преобразование признаков.
- Качество решения: результат метрики MAPE.

### Что практикуем?
Разведывательный анализ данных и проектирование признаков (EDA, Feature Engeneering), участие в соревнованиях на Kaggle.

## Этапы проекта
- Очистка данных
- Проектирование признаков
- Кодирование признаков
- Анализ и отбор признаков
- Обучение модели и получение предсказания
   
## Краткая информация о данных
Данные предоставленные в соревновании:

- hotels_train.csv, набор данных для обучения
- hotels_test.csv, набор данных для оценки качества
- submission.csv, файл сабмишна в нужном формате

## Результаты
Получены предсказания рейтинга для тестового датасета, оформлен submission в соревнование на Kaggle, достигнута метрика качества MAPE=12.96

[Ноутбук с решением](https://github.com/kos-kazakov/sf_data_science/blob/main/Skillfactory%20DS/PROJECT-1/Project-1.%20HeadHunter%20resume%20analysis.ipynb)


__________________________

##  [К оглавлению](https://github.com/kos-kazakov/sf_data_science/blob/main/Skillfactory%20DS/PROJECT-1/README.md#Оглавление)

