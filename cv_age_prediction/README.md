# Обработка фотографий покупателя (CV)

Задача регрессии — определение возраста покупателя по фотографии его лица.

Метрика качества – средняя абсолютная ошибка с максимальным приемлемым значением **8**.

Код обучения нейронной сети оформлен в виде функций для работы на сервере с *GPU*, выделенным Практикумом.

Оптимальными гиперпараметрами в этой задаче оказались:
- Метод градиентного спуска: *Adam*
- Функция потерь: *Huber loss*
- Темп обучения:  $0.0001$
- Коэффициент *L2*-регуляризации: $0.01$

Итоговое значение *MAE* — **6**.
