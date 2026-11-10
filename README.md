# Hopfi3721

Небольшие сервисы, которые работают: Telegram-боты, парсеры, мониторинг.
Пишу на Go, Python и Rust, закрываю тестами и запускаю в Docker.

[Сайт с кейсами](https://hopfi3721.github.io) · [Telegram](https://t.me/vospw)

![Go](https://img.shields.io/badge/Go-1.26-00ADD8?logo=go&logoColor=white)
![Python](https://img.shields.io/badge/Python-3.14-3776AB?logo=python&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-1.96-000000?logo=rust&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?logo=sqlite&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)

## Проекты

| Проект | Что делает | Стек |
| :--- | :--- | :--- |
| [pingwatch](https://github.com/Hopfi3721/pingwatch) | мониторинг доступности: алерты в Telegram без спама, дашборд, история и p95 | Go, SQLite, Docker |
| [tg-orders-bot](https://github.com/Hopfi3721/tg-orders-bot) | приём заявок в Telegram: FSM-форма, админ-панель, выгрузка в CSV | Python, aiogram 3, SQLite |
| [go-concurrent-parser](https://github.com/Hopfi3721/go-concurrent-parser) | парсер каталогов в CSV: лимиты, повторы, настраиваемые селекторы | Go |

## Как я работаю

- сначала фиксирую объём: что входит и что не входит в задачу;
- пишу тесты на логику, которую легко сломать молча (состояния, ретраи, границы валидации);
- отдаю работающий сервис, а не набор файлов: README, `.env.example`, Docker, команда запуска.
