# Дипломное задание к курсу «Основы JavaScript»

Сайт-биржа для крипто-стартапа. На этом сайте можно покупать внутреннюю валюту компании **Неткоин** и передавать эту валюту другим пользователям сервиса. 

Есть интерфейс взаимодействия с АPI (бэкендом, где проходят операции с пользователями и денежными средствами), и интерфейс взаимодействия с DOM (графическим интерфейсом, который вы видите в браузере). 

Задачи проекта: сделать так, чтобы данные, введённые пользователем, отправлялись на сервер, а информация, предоставленная сервером, отобразилась пользователю.

## Начало работы

### Настройка сервера

1. Установите [NodeJS](https://nodejs.org/en/) для своей операционной системы.
2. Сделайте форк этого репозитория.
3. Клонируйте форкнутый репозиторий.
4. Откройте терминал и перейдите в папку с клонированным репозиторием.
5. Установите зависимости, выполнив команду `npm install`.

Убедитесь, что выполняете команды с правами администратора.

### Запуск сервера

1. Откройте терминал, перейдите в папку с клонированным репозиторием и выполните команду `npm start`. Убедитесь, что в консоли появилась надпись `Server started at 8000`.
2. Перейдите по [ссылке](http://localhost:8000). Вы увидите интерфейс Биржи Неткоинов.

### Завершение работы сервера

1. Если нужно прекратить работу сервера, нажмите комбинацию клавиш `Ctrl+C`.

## Структура проекта

В проекте есть две страницы:

1. Страница «Вход и регистрация»:

![Страница «Вход и регистрация»](img/loginPage.jpg)

Код для реализации функционала этой страницы в файле `public/loginPage.js`.

2. Страница «Личный кабинет пользователя»:

![Страница «Личный кабинет пользователя»](img/homePage.jpg)

Код для этой страницы в файле `public/homePage.js`.

Файлы `public/loginPage.js` и `public/homePage.js` уже созданы для вас и подключены, дополнительная настройка не требуется.
