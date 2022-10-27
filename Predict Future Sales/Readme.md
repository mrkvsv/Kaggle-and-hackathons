# Predict Future Sales

In this competition I  work with a challenging time-series dataset consisting of daily sales data, kindly provided by one of the largest Russian software firms - 1C Company.

**Goal** - predict total sales for every product and store in the next month.

**Stack:** `pandas` `RandomizedSearchCV` `CatBoost` `lightGBM` `TensorFlow` `Keras` `LSTM`

## Conclusion
Top cities by number of sales:
1. Moscow (60.9%);
2. Yakutsk (12.5%);
3. Saint Petersburg (9.1%);
4. Voronezh (8.8%);
5. Khimki (8.8%).

The most popular items:
1. Фирменный пакет майка 1С Интерес белый;
2. Playstation Store пополнение бумажника: Карта оплаты 1000 руб.;
3. Прием денежных средств для 1С-Онлайн.

The most popular item categories:
1. Кино - DVD;
2. Игры PC - Стандартные издания;
3. Музыка - CD локального производства.

Between 2013 and 2015 sales fell. In December 2013 and 2014 there is a strong increase in sales in contrast to 2015.

The best nodel is LSTM. Test result (RMSE) = 1.18304.
