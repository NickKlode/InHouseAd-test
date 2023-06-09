Тестовое задание InHouseAd | Сервис для проверки сайтов на доступность.

Задание:

Раз в минуту нужно проверять доступны ли сайты из списка и засекать время доступа к ним.
Есть большое кол-во пользователей, которые хотят знать время доступа к сайтам.
У пользователей есть 3 варианта запросов (эндпойнта):
1. Получить время доступа к определенному сайту.
2. Получить имя сайта с минимальным временем доступа.
3. Получить имя сайта с максимальным временем доступа.

И есть администраторы, которые хотят получать статистику количества запросов пользователей по трем вышеперечисленным эндпойнтам.

Запуск:
1. make build
2. make run

Эндпоинты:
1. localhost:8080/search/{url} - Получить время доступа к определенному сайту. 
2. localhost:8080/min - Получить имя сайта с минимальным временем доступа.
3. localhost:8080/max - Получить имя сайта с максимальным временем доступа.
4. localhost:8080/admin - Получить статистику количества запросов пользователей по трем вышеперечисленным эндпойнтам.