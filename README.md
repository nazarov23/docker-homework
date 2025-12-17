# Домашнее задание: PostgreSQL в Docker

## Описание проекта
Проект демонстрирует запуск Spring Boot приложения с использованием PostgreSQL в Docker.

## Структура проекта
- `db-api.jar` - Java приложение (Spring Boot)
- `application.properties` - конфигурация приложения
- `docker-compose.yml` - конфигурация Docker Compose для PostgreSQL
- `.gitignore` - файл игнорирования Git

## Инструкция по запуску

### 1. Запуск PostgreSQL
```bash
docker-compose up -d

