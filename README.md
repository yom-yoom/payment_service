# 📦 Payment Service

## 📄 Описание

Микросервис отвечает за принятие и обработку запросов пользователей на пожертвования, оплату, и использованием системы оплаты Dual Message System

## ⚙️ Технологии

### Основа:

- Java 17
- Spring Boot 3.0.6

### Базы:

- PostgreSQL
- Redis
- Liquibase

### Общение микросервисов:

- Kafka
- OpenFeign

### Тестирование:

- JUnit 5
- Mockito
- AssertJ
- Testcontainers

### Прочее:

- Lombok
- MapStruct
- Springdoc OpenAPI
- CI Pipeline (GitHub Actions)
- JaCoCo
- Slf4j
- Docker
- WebClient

## 🔗 Связанные сервисы

- Account Service - для связи платежей с какими-либо аккаунтами пользователей.
