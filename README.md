# ITMO-ICT-Backend-2022
Курс по бэкенд-разработке в среде Node.JS для Университета ИТМО

# 1. Введение в проблематику серверной веб-разработки
## 1.1. Знакомство со средой Node.JS, пакетным менеджером npm

[Вводная презентация](https://docs.google.com/presentation/d/1jPnw4sra6DSnoHs6OIp7LF9t68blBGKu_FKxSyGUX3k/edit?usp=sharing)

**ДЗ1** (срок: 11.03.2022, 23:59)

Задание:

- Установка npm (8.1.0), node.js (16.13.0)
- Инициализация npm-пакета
- Установка express
- Удаление express/попытка его обновить
- Написание кастомной команды для npm, чтобы можно удалить express командой “npm run rme”

Необходимо сделать отчёт по [шаблону](https://docs.google.com/document/d/1aAUawxv6_5k_Na7bLqrfUFANodyl89uPHXY4IKXS8WE/edit?usp=sharing)

## 1.2. Знакомство с микрофреймворком Express
## 1.3. Знакомство с ORM Sequelize

[Презентация Express + Sequelize](https://docs.google.com/presentation/d/1QAyV4WYFkILzhd-f13J06z94X6vAmWrWlfM6RNvXiGo/edit?usp=sharing)

[Документация Express](http://expressjs.com/en/starter/hello-world.html)
[Документация Sequelize](https://sequelize.org/master/)
[Документация sequelize-cli](https://openbase.com/js/sequelize-cli/documentation)

[Пример, который делали на паре](https://github.com/kantegory/mentoring/tree/master/14_express_example)

**ДЗ2** (срок 25.03.2022, 23:59)

Задание:

- Продумать свою собственную модель пользователя
- Реализовать набор из CRUD-методов для работы с пользователями средствами Express + Sequelize
- Написать запрос для получения пользователя по id/email

Необходимо сделать отчёт по [шаблону](https://docs.google.com/document/d/1aAUawxv6_5k_Na7bLqrfUFANodyl89uPHXY4IKXS8WE/edit?usp=sharing)

## 1.4. Typescript: основы языка
## 1.5. Автоматизация рутинных действий средствами Makefile

[Презентация "Основы TypeScript, работа с Makefile"](https://docs.google.com/presentation/d/11LDwQ0tV_YmnsBNXtNYqB2yoEwfEK8UkzYIH6r0G3GI/edit?usp=sharing)
[Презентация "Основы TypeScript, Sequelize + TypeScript"](https://docs.google.com/presentation/d/14uSAQEZj6Lk-VC5rmvT0Gi1XWO1EX24g3ljL1u4KECg/edit?usp=sharing)

[Статья по основам синтаксиса на Хабре](https://habr.com/ru/company/nix/blog/301002/)
[Статья на Nuances of Programming](https://nuancesprog.ru/p/14210/)
[Карманная книжка по TS](https://typescript-handbook.ru/docs/ts-1/)
[Видео от Хекслет про утилиту make](https://www.youtube.com/watch?v=pK9mF5aK05Q)
[Makefile для самых маленьких, но это больше про C](https://habr.com/ru/post/155201/)
[Введение в make: история](http://pushorigin.ru/bash/make)

[Пример, который делали на паре](https://github.com/kantegory/mentoring/tree/master/15_express_typescript_example)

Источники по поводу использования typescript в ORM:

[Документация пакета sequelize-typescript](https://www.npmjs.com/package/sequelize-typescript)
[Мануал по использованию typescript внутри sequelize](https://sequelize.org/master/manual/typescript.html)
[Документация TypeORM](https://typeorm.io/) (можно использовать в качестве альтернативы Sequelize)

**ЛР1** (срок: 01.04.2022, 23:59)

Нужно написать свой boilerplate на express + sequelize / TypeORM + typescript.

Должно быть явное разделение на:
- модели
- контроллеры
- роуты
- сервисы для работы с моделями (реализуем паттерн “репозиторий”)

Пример: https://github.com/kantegory/express-sequelize-boilerplate 

Другие примеры можно поискать на github, набрав в поиске: "express boilerplate".

**ДЗ3** (срок: 01.04.2022, 23:59)

Составьте Makefile, который будет автоматизировать ваши рутинные действия, такие как:
- проведение миграций через sequelize;
- запуск приложения;
- установка зависимостей и сборка приложения.

# 2. Тестирование, разработка и документирование RESTful API

# 3. Развёртывание, микросервисы, CI/CD
