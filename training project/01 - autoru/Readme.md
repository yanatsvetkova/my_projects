Определение стоимости автомобилей
Сервис по продаже автомобилей с пробегом «Не бит, не крашен» разрабатывает приложение для привлечения новых клиентов. В нём можно быстро узнать рыночную стоимость своего автомобиля. В нашем распоряжении исторические данные: технические характеристики, комплектации и цены автомобилей. Нам нужно построить модель для определения стоимости.
Заказчику важны:
•	качество предсказания;
•	скорость предсказания;
•	время обучения.
Выводы:
•	Наилучшей по точности и времени предсказания стала модель CatBoostRegressor с показателем 1301 за 0.210 мс, но она проигрывает по времени обучения LinearRegression и LGBMRegressor (3.22 и 25.18 соответственно) со своими 125 с.
Стек:
•	matplotlib, numpy, pandas, sklearn, catboost, lightgbm
Статус проекта:
•	Завершен.
