# moscow_places
Анализ рынка общественного питания Москвы. Проект из курса Яндекс.Практикума "Аналитик данных".

Данные предоставлены из Яндекс Карт и Яндекс Бизнеса.

csv-файл moscow_places содержит колонки со следующей информацией.

 - name — название заведения;
 - address — адрес заведения;
 - category — категория заведения, например «кафе», «пиццерия» или «кофейня»;
 - hours — информация о днях и часах работы;
 - lat — широта географической точки, в которой находится заведение;
 - lng — долгота географической точки, в которой находится заведение;
 - rating — рейтинг заведения по оценкам пользователей в Яндекс Картах (высшая оценка — 5.0);
 - price — категория цен в заведении, например «средние», «ниже среднего», «выше среднего» и так далее;
 - avg_bill — строка, которая хранит среднюю стоимость заказа в виде диапазона, например:
     «Средний счёт: 1000–1500 ₽»;
     «Цена чашки капучино: 130–220 ₽»;
     «Цена бокала пива: 400–600 ₽».
     и так далее;
 - middle_avg_bill — число с оценкой среднего чека, которое указано только для значений из столбца avg_bill, начинающихся с подстроки «Средний счёт»:
     Если в строке указан ценовой диапазон из двух значений, в столбец войдёт медиана этих двух значений.
     Если в строке указано одно число — цена без диапазона, то в столбец войдёт это число.
     Если значения нет или оно не начинается с подстроки «Средний счёт», то в столбец ничего не войдёт.
 - middle_coffee_cup — число с оценкой одной чашки капучино, которое указано только для значений из столбца avg_bill, начинающихся с подстроки «Цена одной чашки    капучино»:
     Если в строке указан ценовой диапазон из двух значений, в столбец войдёт медиана этих двух значений.
     Если в строке указано одно число — цена без диапазона, то в столбец войдёт это число.
     Если значения нет или оно не начинается с подстроки «Цена одной чашки капучино», то в столбец ничего не войдёт.
 - chain — число, выраженное 0 или 1, которое показывает, является ли заведение сетевым (для маленьких сетей могут встречаться ошибки):
     0 — заведение не является сетевым
     1 — заведение является сетевым
 - district — административный район, в котором находится заведение, например Центральный административный округ;
 - seats — количество посадочных мест.
 
