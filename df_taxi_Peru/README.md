# [df_taxi_Peru](https://disk.yandex.ru/d/5OUzhWvyi0n1DA)

### [Анализ данных](https://github.com/KristinaLyu/Tasks_from_Karpov_courses/blob/main/df_taxi_Peru/df_taxi_Peru.ipynb)


Вернемся к данным по поездкам на такси. На этот раз – из Перу, с рейтингами водителей, пассажиров, координатами, и парой других деталей.

**journey_id** – уникальный id поездки  
**user_id** – id пользователя  
**driver_id** – id водителя  
**taxi_id** – id машины  
**icon** – тип поездки  
**start_type** – тип заказа (asap, reserved, delayed)  
**start_at** – время начала поездки  
**start_lat** – исходное местоположение пользователя, широта  
**start_lon** – исходное местоположение пользователя, долгота  
**end_at** – время окончания поездки  
**end_lat** – итоговое местоположение, широта  
**end_lon** – итоговое местоположение, долгота  
**end_state** – состояние заказа  
**driver_start_lat** – исходное местоположение водителя, широта  
**driver_start_lon** – исходное местоположение водителя, долгота  
**arrived_at** – время прибытия водителя  
**source** – платформа, с которой сделан заказ  
**driver_score** – оценка водителя клиентом  
**rider_score** – оценка клиента водителем  
 

Требуется указать, что столбцы `start_at`, `end_at`, `arrived_at` нужно прочитать как даты (параметр `parse_dates`).
Результат запишем в переменную `taxi`.
