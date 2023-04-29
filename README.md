###Data analysis of cian apartments
Финальный проект по курсу "Модели и архитектуры программ и знаний". В репозитории представлен анализ объявлений о продаже квартир с сайта https://spb.cian.ru/ в Санкт-Петербурге.



###Датасет
Набор данных содержит 7920 записей и состоит из следующих колонок:

* Цена (₽)
* Количество комнат
* Площадь (м²)
* Этаж
* Всего этажей в доме
* Наличие метро в шаговой доступности
* Сдана квартира или нет


###Гипотезы
После обработки и визуализации данных были выдвинуты следующие гипотезы:

 * Чем больше площадь жилья, тем больше стоимость
 * Однокомнатные квартиры сдаются чаще чем двухкомнатные
 * Наличие метро в шаговой доступности влияет на цену за квадратный метр
 * Если квартиры находятся на первых двух этажах, то они стоят дешевле
 
###Обучение моделей
Для предсказания цен на квартиры были обучены 3 модели машинного обучения:
* Logistic Regression
* Decision Tree Regressor
* Random Forest Regressor

Наилучший результат показал Random Forest Regressor — score: 0.9896303743981283
