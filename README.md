Задание 25.5.1. В написанном тесте (проверка карточек питомцев) добавьте неявные ожидания всех элементов (фото, имя питомца, его возраст). В написанном тесте (проверка таблицы питомцев) добавьте явные ожидания элементов страницы. Чеклист для самопроверки:

В тестах используется настройка implicitly-wait веб-драйвера.

В тестах используются элементы класса WebDriverWait.

 python -m pytest -v --driver Chrome --driver-path C:</chromedriver_win32>/chromedriver test_PetFriends.py  для запуска терминала
