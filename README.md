<h1 align="center">Андрей Бурдак</h1>
<h3 align="center">Java Backend Developer</h3>

<p align="center">
  Разрабатываю серверные приложения на Java и Spring Boot: REST API, проектирование БД, миграции, тестирование и контейнеризация.
</p>

<p align="center">
  <a href="https://t.me/burdak_aa"><img src="https://img.shields.io/badge/Telegram-@burdak__aa-26A5E4?logo=telegram&logoColor=white" alt="Telegram"></a>
  <a href="mailto:burdak.andrew@gmail.com"><img src="https://img.shields.io/badge/Email-burdak.andrew@gmail.com-EA4335?logo=gmail&logoColor=white" alt="Email"></a>
</p>

<p align="center"><b>Русский</b> · <a href="#english">English</a></p>

---

## Обо мне

Java backend-разработчик. Создаю REST-сервисы на Spring Boot полного цикла: от модели данных и миграций до тестов и развёртывания в Docker.

- **Архитектура:** монолиты со слоистой структурой и микросервисы с межсервисным HTTP-взаимодействием.
- **Данные:** проектирую схемы PostgreSQL, индексы под реальные запросы, миграции Liquibase, JSONB, атомарные UPSERT для конкурентной записи.
- **Качество:** юнит- и интеграционные тесты на JUnit 5, Mockito и Testcontainers, контрактные проверки API в Postman, CI на GitHub Actions.
- **Инфраструктура:** Docker и Docker Compose, OpenAPI/Swagger, Checkstyle и SpotBugs.

## Стек

**Язык и фреймворки**
![Java](https://img.shields.io/badge/Java_21-ED8B00?logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?logo=springboot&logoColor=white)
![Spring Data JPA](https://img.shields.io/badge/Spring_Data_JPA-6DB33F?logo=spring&logoColor=white)
![Hibernate](https://img.shields.io/badge/Hibernate-59666C?logo=hibernate&logoColor=white)

**Данные**
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)
![Liquibase](https://img.shields.io/badge/Liquibase-2962FF?logo=liquibase&logoColor=white)

**Тестирование**
![JUnit 5](https://img.shields.io/badge/JUnit_5-25A162?logo=junit5&logoColor=white)
![Mockito](https://img.shields.io/badge/Mockito-78A641)
![Testcontainers](https://img.shields.io/badge/Testcontainers-291A3F?logo=testcontainers&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?logo=postman&logoColor=white)

**Инструменты**
![Maven](https://img.shields.io/badge/Maven-C71A36?logo=apachemaven&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?logo=githubactions&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white)
![IntelliJ IDEA](https://img.shields.io/badge/IntelliJ_IDEA-000000?logo=intellijidea&logoColor=white)

## Проекты

| Проект | Описание | Стек |
| --- | --- | --- |
| [**Game Service**](https://github.com/pochette/gameService) | REST-сервис для хранения состояния игроков, событий активности и аналитики. Гонка при конкурентной записи устранена атомарным PostgreSQL UPSERT. | Spring Boot 4, PostgreSQL (JSONB), Liquibase, Testcontainers, Docker |
| [**Explore With Me**](https://github.com/pochette/explore-with-me) | Афиша событий на микросервисах: основной сервис и отдельный сервис статистики просмотров. | Spring Boot 3, PostgreSQL, Docker Compose, GitHub Actions |
| [**ShareIt**](https://github.com/pochette/java-shareit) | Сервис аренды вещей: бронирования, подтверждение владельцем, отзывы. | Spring Boot 3, Spring Data JPA, PostgreSQL |
| [**Filmorate**](https://github.com/pochette/java-filmorate) | REST API фильмотеки: лайки, друзья, популярные фильмы, справочники жанров и MPA. | Spring Boot, PostgreSQL, JUnit 5 |
| [**Later**](https://github.com/pochette/module-4-later-spring-only) | Миграция легаси-приложения со Spring Framework на Spring Boot с тестами и контейнеризацией. | Spring Framework 6 → Spring Boot 3, Hibernate, Docker |

## Образование

- **Высшее** — Академия ИМСИТ, прикладная информатика.
- **Профессиональная переподготовка** — Яндекс Практикум, «Java-разработчик».

---

<a id="english"></a>

<details>
<summary><b>English version</b></summary>

## About

Java backend developer. I build Spring Boot REST services end to end: from the data model and migrations to tests and Docker deployment.

- **Architecture:** layered monoliths and microservices communicating over HTTP.
- **Data:** PostgreSQL schema design, indexes tailored to real queries, Liquibase migrations, JSONB, atomic UPSERTs for concurrent writes.
- **Quality:** unit and integration tests with JUnit 5, Mockito and Testcontainers, API contract checks in Postman, CI with GitHub Actions.
- **Infrastructure:** Docker and Docker Compose, OpenAPI/Swagger, Checkstyle and SpotBugs.

## Projects

| Project | Description | Stack |
| --- | --- | --- |
| [**Game Service**](https://github.com/pochette/gameService) | REST service for player state, activity events and analytics. A concurrent-write race condition was fixed with an atomic PostgreSQL UPSERT. | Spring Boot 4, PostgreSQL (JSONB), Liquibase, Testcontainers, Docker |
| [**Explore With Me**](https://github.com/pochette/explore-with-me) | Microservice-based event platform: main service plus a separate view-statistics service. | Spring Boot 3, PostgreSQL, Docker Compose, GitHub Actions |
| [**ShareIt**](https://github.com/pochette/java-shareit) | Item-sharing service: bookings, owner approval, reviews. | Spring Boot 3, Spring Data JPA, PostgreSQL |
| [**Filmorate**](https://github.com/pochette/java-filmorate) | Film library REST API: likes, friends, popular films, genre and MPA dictionaries. | Spring Boot, PostgreSQL, JUnit 5 |
| [**Later**](https://github.com/pochette/module-4-later-spring-only) | Migration of a legacy app from Spring Framework to Spring Boot, with tests and containerization. | Spring Framework 6 → Spring Boot 3, Hibernate, Docker |

## Education

- **Higher education** — IMSIT Academy, Applied Informatics.
- **Professional retraining** — Yandex Practicum, Java Developer program.

**Contact:** [Telegram @burdak_aa](https://t.me/burdak_aa) · [burdak.andrew@gmail.com](mailto:burdak.andrew@gmail.com)

</details>
