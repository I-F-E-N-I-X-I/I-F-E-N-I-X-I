# Игорь Цветков

Начинающий **Java Backend-разработчик**, также развиваюсь в **C# / .NET**. Интересуют серверная логика, REST API, базы данных и инструменты для разработчиков.

В портфолио — проекты с исходным кодом, инструкциями запуска и проверяемыми результатами.

## Java-проект — SupportFlow

**Система обработки обращений клиентов с отдельным сервисом уведомлений.**

Роли CLIENT/SUPPORT/ADMIN, назначение сотрудников, статусы, комментарии, история, поиск и статистика. События доставляются через transactional outbox и RabbitMQ; Redis кэширует справочник, а уведомления хранятся в отдельной базе.

Стек: Java 21, Spring Boot, JPA/Hibernate, PostgreSQL, JWT, RabbitMQ, Redis, Flyway, Gradle, Docker Compose. Проверки: JUnit 5, Mockito, MockMvc, Testcontainers и сценарии отказов зависимостей в GitHub Actions.

[Репозиторий и запуск](https://github.com/I-F-E-N-I-X-I/supportflow/tree/feature/supportflow) · [Архитектура](https://github.com/I-F-E-N-I-X-I/supportflow/blob/feature/supportflow/docs/ARCHITECTURE.md) · [Карта технологий и учебных примеров](https://github.com/I-F-E-N-I-X-I/supportflow/blob/feature/supportflow/docs/REQUIREMENTS.md) · [CI](https://github.com/I-F-E-N-I-X-I/supportflow/actions)

Учебный проект подготовлен с помощью AI-ассистента. В отдельном модуле — проверяемые упражнения по Java, коллекциям, алгоритмам и многопоточности. [Процесс разработки](https://github.com/I-F-E-N-I-X-I/supportflow/blob/feature/supportflow/docs/DEVELOPMENT.md).

## Java-проект — ReserveHub

**Backend для бронирования и выдачи оборудования на Java и Spring Boot.**

Регистрация и роли, каталог, резервирование, выдача и возврат, история операций. Транзакции и SQL-блокировки защищают остатки при одновременных запросах. Доступ к данным реализован через Spring JDBC, без Hibernate ORM.

[Репозиторий и запуск](https://github.com/I-F-E-N-I-X-I/reservehub) · [REST API](https://github.com/I-F-E-N-I-X-I/reservehub/blob/main/docs/API.md) · [Архитектура](https://github.com/I-F-E-N-I-X-I/reservehub/blob/main/docs/ARCHITECTURE.md) · [Тесты и CI](https://github.com/I-F-E-N-I-X-I/reservehub/actions)

Стек проекта: Java 21, Spring Boot, Spring Security, Spring JDBC, SQL, PostgreSQL, Flyway, JUnit 5, Docker. Автоматические проверки покрывают бизнес-правила, безопасность, транзакции и конкурентный доступ.

Проект подготовлен с помощью AI-ассистента для самостоятельного изучения и дальнейшего развития. [Процесс разработки и план практики](https://github.com/I-F-E-N-I-X-I/reservehub/blob/main/docs/DEVELOPMENT.md).

## Навыки и направления изучения

- Java Core, ООП, Spring, REST API и HTTP — учебная backend-разработка.
- SQL, PostgreSQL/MySQL — запросы и проектирование простых схем данных.
- JUnit, Git/GitHub, Docker и Linux/Ubuntu — тестирование и инструменты разработки.
- Основы микросервисной архитектуры; Hibernate ORM планирую изучить подробнее.
- C# / .NET и Unity — приложения, инструменты и игровые проекты.

## C#-проект — Отклик

**Локальный HTTP mock-сервер для тестирования клиентских приложений.**

Позволяет воспроизвести ошибку сервера, задержку, пустой ответ и восстановление без подключения к настоящему backend. Сценарий `500 → 503 → 200` показывает, как клиент проходит через ошибку, повтор и успешный ответ.

[Репозиторий и скриншот](https://github.com/I-F-E-N-I-X-I/otklik) · [Скачать приложение](https://github.com/I-F-E-N-I-X-I/otklik/releases/latest) · [Архитектура](https://github.com/I-F-E-N-I-X-I/otklik/blob/main/docs/ARCHITECTURE.md)

| В проекте | Где посмотреть |
|---|---|
| C#, модели данных, маршрутизация и правила | [Core](https://github.com/I-F-E-N-I-X-I/otklik/tree/main/src/MockLab.Core) |
| HTTP, Kestrel, асинхронность и отмена | [Server](https://github.com/I-F-E-N-I-X-I/otklik/tree/main/src/MockLab.Server) |
| WPF и редактор конфигурации | [Desktop](https://github.com/I-F-E-N-I-X-I/otklik/tree/main/src/MockLab.Desktop) |
| 49 автоматических проверок и CI | [Проверки](https://github.com/I-F-E-N-I-X-I/otklik/actions) |
| Технические решения и ограничения | [Разбор](https://github.com/I-F-E-N-I-X-I/otklik/blob/main/docs/DESIGN_DECISIONS.md) |

## Направления развития

- Проектирование и тестирование приложений на .NET.
- Сетевое взаимодействие и воспроизводимые сценарии проверки API.
- Разделение логики приложения и интерфейса.
- Более глубокая автоматизация тестирования и работа с CI.

Проект выполнен в учебном контексте. О процессе разработки и использовании инструментов — [в документации проекта](https://github.com/I-F-E-N-I-X-I/otklik/blob/main/docs/DEVELOPMENT.md).
