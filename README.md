# Зимина Елизавета, 14-я когорта — Финальный проект. Инженер по тестированию плюс
Проект содержит автотесты к API. Проверяется, что по треку заказа можно получить данные о заказе

Шаги автотеста:
1. Выполнить запрос на создание заказа.
2. Сохранить номер трека заказа.
3. Выполнить запрос на получения заказа по треку заказа.
4. Проверить, что код ответа равен 200.

Для запуска тестов должны быть установлены пакеты pytest и requests
- Запуск всех тестов выполянется командой pytest

Логи лежат в файле error.log в папке /var/www/backend/logs
