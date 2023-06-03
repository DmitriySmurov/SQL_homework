---
## Урок 2. SQL – создание объектов, простые запросы выборки
---
##### * Используя операторы языка SQL, создайте табличку “sales”. Заполните ее данными._
##### * Сгруппируйте значений количества в 3 сегмента — меньше 100, 100-300 и больше 300._
##### * Создайте таблицу “orders”, заполните ее значениями. Покажите “полный” статус заказа, используя оператор CASE._
##### * Чем NULL отличается от 0?_


### Урок 3. SQL – выборка данных, сортировка, агрегатные функции
---
##### * Отсортируйте данные по полю заработная плата (salary) в порядке: убывания; возрастания.
##### * Выведите 5 максимальных заработных плат (saraly).
##### * Посчитайте суммарную зарплату (salary) по каждой специальности (роst).
##### * Найдите кол-во сотрудников с специальностью (post) «Рабочий» в возрасте от 24 до 49 лет включительно.
##### * Найдите количество специальностей.
##### * Выведите специальности, у которых средний возраст сотрудников меньше 30 лет включительно.


### Урок 4. SQL – работа с несколькими таблицами
---
##### * Подсчитать общее количество лайков, которые получили пользователи младше 12 лет
##### * Определить кто больше поставил лайков (всего): мужчины или женщины
##### * Вывести всех пользователей, которые не отправляли сообщения.
##### * (по желанию)* Пусть задан некоторый пользователь. Из всех друзей этого пользователя найдите человека, который больше всех написал ему сообщений.

### Урок 5. SQL – оконные функции
---
##### * Создайте представление, в которое попадут автомобили стоимостью до 25 000 долларов CREATE VIEW CheapCars AS SELECT Name FROM Cars WHERE Cost<25000;
##### * Изменить в существующем представлении порог для стоимости: пусть цена будет до 30 000 долларов (используя оператор ALTER VIEW) ALTER VIEW CheapCars AS SELECT Name FROM CarsWHERE Cost<30000;
##### * Создайте представление, в котором будут только автомобили марки “Шкода” и “Ауди” (аналогично) Вывести название и цену для всех анализов, которые продавались 5 февраля 2020 и всю следующую неделю. Есть таблица анализов Analysis: an_id — ID анализа; an_name — название анализа; an_cost — себестоимость анализа; an_price — розничная цена анализа; an_group — группа анализов. Есть таблица групп анализов Groups: gr_id — ID группы; gr_name — название группы; gr_temp — температурный режим хранения. Есть таблица заказов Orders: ord_id — ID заказа; ord_datetime — дата и время заказа; ord_an — ID анализа.

