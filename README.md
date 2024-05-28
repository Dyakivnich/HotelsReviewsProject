
# Проект выявления накрутки рейтинга отелей

## Задача проекта

Исследовать [данные](https://www.kaggle.com/competitions/sf-booking/data?select=hotels_test.csv) отзывов отелей. 

Построить модель, которая будет предсказывать рейтинг отелей.

## Информация по проекту

Вспомогательные [данные](https://github.com/Dyakivnich/HotelsReviewsProject/blob/master/country_population.csv) по странам.

В качестве метрики качества применяем MAPE (средняя абсолютная процентная ошибка).

Для обучения модели применили RandomForestRegressor.

## Общие выводы

Получившееся значения MAPE равно 13.5 %.
