# Intershop — API & Security Testing

## 🌐 О проекте

**Intershop** — веб-приложение интернет-магазина.

В рамках данного этапа разработки было проведено тестирование REST API интернет-магазина, проверка взаимодействия между клиентской и серверной частью, а также базовое тестирование безопасности веб-приложения.

Особое внимание уделялось корректности работы HTTP-методов, проверке бизнес-логики API, синхронизации данных между Backend и UI, а также поиску потенциальных уязвимостей.

---

# 🛠 Используемые инструменты

- Postman
- Google Chrome
- Chrome DevTools
- Google Sheets
- YouGile

---

# 📋 Выполненные работы

## 1. API Testing (POST)

Изучен процесс тестирования API с использованием Postman.

Проведено тестирование метода **POST**.

Проверены:

- негативные сценарии;
- обработка некорректных данных;
- корректность ответов сервера.

### Документы

- POST Test Cases - (https://docs.google.com/spreadsheets/d/1Jauzo2EAabvybQwAs0FGY8rTP_s_9HQaW1CK-0cEh5Q/edit?gid=0#gid=0)
- Bug Reports - (https://yougile.com/board/cde4qt643vdj)

---

## 2. API Testing (PUT & DELETE)

Подготовлены и выполнены тесты для методов:

- PUT
- DELETE

Проверены:

- успешное изменение данных;
- успешное удаление данных;
- обработка некорректных запросов;
- обработка отсутствующих ресурсов;
- корректность HTTP Status Codes;
- структура ответов API.

### Документы

- PUT & DELETE Test Cases - (https://docs.google.com/spreadsheets/d/10uHAtr19uj_hxud1gJ6xmfw3SnHZCf59JEUCK0udhvc/edit?gid=0#gid=0)
- Bug Reports - (https://yougile.com/board/rujfqulgmprc)

---

## 3. API + UI Integration Testing

Проведено комплексное тестирование новой функциональности отображения остатков товара.

Проверены:

- отображение остатков товара в интерфейсе;
- соответствие данных UI и Backend;
- обновление количества товара после оформления заказа;
- граничные значения количества товара;
- невозможность заказать товара больше, чем имеется на складе.

### Документы

- API/UI Test Cases - (https://docs.google.com/spreadsheets/d/1fPyFBv6D3yENnK_0L22w2GVOFL9bsAkDlZ4nexWGXeM/edit?gid=0#gid=0)
- Bug Reports - (https://yougile.com/board/4ovengcwuhgc)

---

## 4. Security Testing

Проведено базовое тестирование безопасности приложения.

Проверены:

- обработка промокодов;
- защита системы скидок;
- XSS;
- SQL Injection;
- обработка пользовательского ввода;
- проверка URL-параметров;
- попытки получения доступа к чужим данным.

### Документы

- Security Test Cases - (https://docs.google.com/spreadsheets/d/1ZowlR4C1Oq1X2PJrpm8HiwxeD_IkG0kU-qK8JDR6QSk/edit?pli=1&gid=0#gid=0)
- Bug Reports - (https://yougile.com/board/8aq7v3i11qew)

---

# 🎯 Что демонстрирует данный проект

В рамках проекта были применены следующие навыки:

- REST API Testing
- Postman
- HTTP Methods (GET, POST, PUT, DELETE)
- HTTP Status Codes
- API Validation
- Backend Testing
- Frontend & Backend Integration Testing
- UI/API Testing
- Boundary Value Analysis
- Security Testing
- XSS Testing
- SQL Injection Testing
- Business Logic Testing
- Bug Reporting
- Test Case Design
- Работа с Google Sheets
- Работа с YouGile

---

# 👨‍💻 Автор

**Святослав Феньев**

QA Engineer (Manual Testing)
