# Data-Base 
# Лабораторная работа 1 по дисциплине "Базы данных"
## Осипов Павел Артёмович, 2261-ДБ
## Вариант 23: "Туристическое агентство"
Информация о клиенте (ФИО, данные паспорта). Информация о поездке (страна назначения, стоимость 1 дня пребывания, стоимость транспортных услуг).
При этом цели поездок могут быть различными (отдых, туризм, лечение и т.д.).
Накапливается информация о маршрутах поездок клиентов, где хранятся цель поездки, стоимость оформления визы (определяется выбором маршрута), дата начала поездки, количество дней 

Выходные документы:
Список маршрутов клиентов за определенный период с указанием стоимости каждой поездки.
Стоимость поездки может быть вычислена как Стоимость 1 дня пребывания. Количество дней + Стоимость транспортных услуг + Стоимость оформления визы.
Кроме того, клиент платит налог на добавленную стоимость (НДС) в размере 18% от стоимости поездки.
Список поездок, отсортированный по странам

## ER-диаграмма
![ER диаграмма](https://github.com/dodgetill/Data-Base/blob/main/Untitled%20diagram%20_%20Mermaid%20Chart-2025-10-07-042402.png)
# Лабораторная работа 2 по дисциплине "Базы данных"
## Создаём 4 таблицы с записанными в них данными
![](https://github.com/dodgetill/Data-Base/blob/main/лаба2/photo_1_2025-12-15_19-35-44.jpg)
![](https://github.com/dodgetill/Data-Base/blob/main/лаба2/photo_3_2025-12-15_19-35-44.jpg)
### После создания таблиц, выводим их для для проверки
![](https://github.com/dodgetill/Data-Base/blob/main/лаба2/photo_2_2025-12-15_19-35-44.jpg)
![](https://github.com/dodgetill/Data-Base/blob/main/лаба2/photo_4_2025-12-15_19-35-44.jpg)
![](https://github.com/dodgetill/Data-Base/blob/main/лаба2/photo_5_2025-12-15_19-35-44.jpg)
![](https://github.com/dodgetill/Data-Base/blob/main/лаба2/photo_6_2025-12-15_19-35-44.jpg)
### Далее выполняем SELECT-запросы с JOIN
![](https://github.com/dodgetill/Data-Base/blob/main/лаба2/photo_7_2025-12-15_19-35-44.jpg)
![](https://github.com/dodgetill/Data-Base/blob/main/лаба2/photo_8_2025-12-15_19-35-44.jpg)
# Лабораторная работа 3 по дисциплине "Базы данных"
## Создадим 2 представления
![](https://github.com/dodgetill/Data-Base/blob/main/лаба3/лаба%203%2C%20представления.png)
## Первая процедура
![](https://github.com/dodgetill/Data-Base/blob/main/лаба3/процедура%201.png)
## Вторая процедура
![](https://github.com/dodgetill/Data-Base/blob/main/лаба3/процедура%202.png)
## Результат двух представлений
![](https://github.com/dodgetill/Data-Base/blob/main/лаба3/вызов%20представлений.png)
## Результат первой процедуры
![](https://github.com/dodgetill/Data-Base/blob/main/лаба3/вызов%20процедуры%201.png)
## Результат второй процедуры
![](https://github.com/dodgetill/Data-Base/blob/main/лаба3/вызов%20процедуры%202.png)
# Лабораторная работа 4 по дисциплине "Базы данных"
## Генератор клиентов
![](https://github.com/dodgetill/Data-Base/blob/main/лаба4/ген%20клиентов.png)
## Генератор стран
![](https://github.com/dodgetill/Data-Base/blob/main/лаба4/ген%20страны.png)
## Генератор цели
![](https://github.com/dodgetill/Data-Base/blob/main/лаба4/ген%20цели.png)
## Анализ запросов
![](https://github.com/dodgetill/Data-Base/blob/main/лаба4/Снимок%20экрана%202025-12-15%20201920.png)
## Создал индекс
![](https://github.com/dodgetill/Data-Base/blob/main/лаба4/Снимок%20экрана%202025-12-15%20202045.png)
# Лабораторная работа 5 по дисциплине "Базы данных"
## 1. Триггер каскадного удаления маршрутов при удалении клиента
![](https://github.com/dodgetill/Data-Base/blob/main/лаба5/Снимок%20экрана%202025-12-15%20210040.png)
## Проверка
![](https://github.com/dodgetill/Data-Base/blob/main/лаба5/Снимок%20экрана%202025-12-15%20205854.png)
## 2. Триггер каскадного удаления маршрутов при удалении страны
![](https://github.com/dodgetill/Data-Base/blob/main/лаба5/Снимок%20экрана%202025-12-15%20210102.png)
## 3. Создание таблицы аудита для маршрутов
![](https://github.com/dodgetill/Data-Base/blob/main/лаба5/Снимок%20экрана%202025-12-15%20210158.png)
## 4. Функция и триггер аудита для маршрутов
![](https://github.com/dodgetill/Data-Base/blob/main/лаба5/Снимок%20экрана%202025-12-15%20210226.png)
## 5. Функция генерации тестовых маршрутов
![](https://github.com/dodgetill/Data-Base/blob/main/лаба5/Снимок%20экрана%202025-12-15%20210254.png)
## 6. Тестирование триггеров аудита
![](https://github.com/dodgetill/Data-Base/blob/main/лаба5/Снимок%20экрана%202025-12-15%20210314.png)
## 7. Проверка результатов аудита
![](https://github.com/dodgetill/Data-Base/blob/main/лаба5/Снимок%20экрана%202025-12-15%20210355.png)
## 8. Очистка тестовых данных
![](https://github.com/dodgetill/Data-Base/blob/main/лаба5/Снимок%20экрана%202025-12-15%20210407.png)
