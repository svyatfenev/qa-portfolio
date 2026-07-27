# Intershop — Web Application Manual Testing

## 🛒 О проекте

**Intershop** — веб-приложение интернет-магазина.

В рамках проекта было проведено комплексное тестирование веб-приложения на разных этапах разработки: анализ требований, исследовательское тестирование, функциональное тестирование основных разделов магазина, проверка сетевых запросов через DevTools, дымовое, повторное и регрессионное тестирование.

---

# 🛠 Используемые инструменты

- Google Chrome
- Chrome DevTools (Network)
- Google Sheets
- YouGile

---

# 📋 Выполненные работы

## 1. Анализ требований

Проведён анализ технической спецификации приложения.

В ходе проверки были выявлены логические ошибки и несоответствия требований.

### Документы

- Review требований - (https://docs.google.com/document/d/1aR9cSupbGtCsK3b29FlRiFrVNVaB3xD2TS1FaCl6HGQ/edit?hl=ru&tab=t.0)
- Bug Reports (Requirements Review) - (https://yougile.com/board/eo9p3k221f94#ET-1)

---

## 2. Исследовательское тестирование регистрации и авторизации

Проведено исследовательское тестирование форм регистрации и авторизации.

Подготовлен чек-лист проверки основных пользовательских сценариев.

Проверены:

- регистрация пользователя;
- авторизация;
- обязательные поля;
- валидация;
- обработка ошибок;
- негативные сценарии.

### Документы

- Test Cases - (https://docs.google.com/spreadsheets/d/1QXJ-cOdq6iL9Eb35WxB5nO3z1_5jlUCXE2RMMRbIRSo/edit?gid=0#gid=0)
- Bug Reports - (https://yougile.com/board/eo9p3k221f94#ET-20)

---

## 3. Функциональное тестирование

Подготовлены тест-кейсы и выполнено тестирование:

- Главной страницы;
- Каталога товаров;
- Карточки товара;
- Корзины.

Дополнительно выполнена проверка сетевого взаимодействия через Chrome DevTools.

Проверено:

- HTTP-запросы;
- ответы сервера;
- статус-коды;
- корректность возвращаемых данных.

Также была выполнена оценка времени выполнения тестирования и сравнение с фактическими трудозатратами.

### Документы

- Functional Test Cases - (https://docs.google.com/spreadsheets/d/1QD7llIhlonHp4o23NNlQ3KsFZXAVX1kiHi5OMKEAFHI/edit?gid=0#gid=0)
- Bug Reports - (https://yougile.com/board/a2r1bc0pm3sz#ET-61)

---

## 4. Smoke Testing

Проведено дымовое тестирование процесса оформления заказа.

Проверены критические пользовательские сценарии:

- оформление заказа;
- заполнение данных;
- выбор способа оплаты;
- подтверждение заказа.

### Документы

- Smoke Test Cases - (https://docs.google.com/spreadsheets/d/1s4TbzneEJGlQ3kqjDTrrlxI5D-0yQESr1dL8a9yy8Vc/edit?hl=ru&gid=0#gid=0)
- Bug Reports - (https://yougile.com/board/edxjx9zgr1nt#ET-96)

---

## 5. Regression & Retesting

После исправления дефектов выполнены:

- повторное тестирование исправленных багов (Retesting);
- регрессионное тестирование основных функций приложения.

По результатам подготовлен итоговый отчёт.

### Документы

- Regression Test Cases - (https://docs.google.com/spreadsheets/d/19Vpq8TCcTSxnaN2VvMZS5ZR0XZiGVnb5ryAAhQyW4wo/edit?gid=0#gid=0)
- Test Report - (https://docs.google.com/document/d/1UCzM6Kvtk1H5FWbgHX0xeZ5uxhYH-7cL/edit)
- Bug Reports - (https://yougile.com/board/jf2s3tpc5nh4)

---

# 🎯 Что демонстрирует данный проект

В рамках проекта были применены следующие навыки:

- Requirements Analysis
- Exploratory Testing
- Checklist Design
- Test Case Design
- Functional Testing
- Smoke Testing
- Regression Testing
- Retesting
- Web UI Testing
- HTTP Request Validation
- Chrome DevTools (Network)
- Status Code Validation
- Bug Reporting
- Test Reporting
- Test Estimation
- Работа с Google Sheets
- Работа с YouGile

---

# 👨‍💻 Автор

**Святослав Феньев**

QA Engineer (Manual Testing)
