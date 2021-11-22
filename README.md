# Тестовое задание от https://avsw.ru/

Датасет описывает некоторую зависимость числа ***bugs*** от
значений ***repository_name***, ***commit_hash***, ***commit_date***,
***commit_author***, *commit_message*. Необходимо выявить
данную зависимость и написать скрипт/ноутбук, обучающий
модель по данному датасету

Обученно несколько моделей:
* LinearRegression
* Lasso
* Ridge
* LassoCV
* RidgeCV
* RandomForestRegressor

Лучшее значение RMSE = 1.84 получено для модели RidgeCV(cv=2)
