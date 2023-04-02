## QAP_HW_25.5.1_API_PetFriends_tests
___
### Тестовый проект к модулю №25 SkillFactory курса QAP

В корневой директории находятся:
* файл settings.py - содержит информацию о логине, пароле и url
* файл conftest.py - содержит фикстуру для инициализации драйвер-браузера и закрытия сессии после завершения теста
* файл autorisation.py - содержит метод авторизации на сайте

В директории /tests располагается файл с тестами

Тесты проверяют:
* удачную авторизацию на сайте
* элементы карточек питомцев (фото, имя, описание)
* элементов страницы

В тестах используются:

✅ implicitly-wait веб-драйвера

✅ элементы класса WebDriverWait
