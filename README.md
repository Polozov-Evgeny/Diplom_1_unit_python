## **Дипломный проект "Яндекс Практикум". Часть 1: Unit-tests**

### Юнит-тесты для проверки программы, которая помогает заказать бургер в Stellar Burgers

1. Ссылка на сайт: *https://stellarburgers.nomoreparties.site/*
2. Созданы юнит-тесты, покрывающие классы `Bun`, `Burger`, `Ingredient`, `Database`

### Структура проекта

- `praktikum` - пакет, содержащий код программы
- `tests` - пакет, содержащий юнит-тесты

### Запуск автотестов

**Установка зависимостей**

> `$ pip install -r requirements.txt`

**Запуск автотестов и создание HTML-отчета о покрытии**

>  `$ pytest --cov=practicum --cov-report=html`
