# Задание на Лекцию 1 — Проект: Мобильное приложение для официантов

### Заказчик:

Сеть ресторанов, которая стремится оптимизировать взаимодействие официантов с кухней и клиентами.

### Проблемы:

- Официанты не имеют удобного инструмента для записи заказов.
- Задержки в подаче блюд из-за отсутствия системы для отслеживания статуса заказа.
- Отсутствие интеграции с кассовыми системами и учетными системами ресторана.

### Потенциальное решение:

Мобильное приложение для официантов, которое позволит:

- Вводить заказы напрямую в систему.
- Отслеживать статус заказа на кухне.
- Интеграцию с кассовыми системами и CRM для учета продаж и автоматизации.

### Методология разработки:

**Agile**, с акцентом на непрерывное взаимодействие с заказчиком, регулярные спринты, быструю обратную связь и улучшения в процессе разработки.

## Этапы жизненного цикла проекта:

### 1. Инициация проекта и анализ требований

- **1.1 Первая встреча с заказчиком:** обсуждение проблем, выявление ключевых потребностей.
- **1.2 Определение целей и ключевых функций:** создание общего видения проекта с акцентом на MVP.
  - Основные функции:
    - Добавление заказа официантами.
    - Уведомления о готовности блюд.
    - Возможность редактирования заказа.
    - Интеграция с кассовой системой.

### 2. Планирование

- **2.1 Формирование команды:**
  - **Владелец продукта (PO)** – представитель заказчика.
  - **Проектный менеджер (PM)** – контролирует процесс разработки.
  - **Бизнес-аналитик** – собирает требования и общается с заказчиком.
  - **Системный аналитик** – отвечает за технические требования.
  - **UI/UX-дизайнер** – создает удобный интерфейс для официантов.
  - **Архитектор БД** – проектирует структуру базы данных.
  - **Разработчики (Frontend и Backend)** – отвечают за разработку мобильного и серверного приложения.
  - **QA-инженеры** – проверяют систему на баги.
  - **DevOps** – обеспечивает бесперебойную работу сервиса.
- **2.2 Определение целей первой итерации:**
  - Создание MVP, включающего базовую функциональность для ввода и обработки заказов.
  - Разработка первичного интерфейса.

### 3. Разработка по Agile (итерации)

#### 3.1 Первая итерация (MVP)

**Цель:** Реализовать минимальный функционал для ввода и отображения заказов.

- **3.1.1 Прототипирование и дизайн:**
  - UI/UX-дизайнер создает интерфейс, ориентированный на удобство официантов (быстрый доступ к заказам, статус блюд, удобная навигация).
  - Прототип обсуждается с заказчиком.
- **3.1.2 Разработка:**
  - Мобильные разработчики создают базовое приложение.
  - Backend-разработчики проектируют серверную часть для хранения данных заказов.
- **3.1.3 Тестирование:**
  - QA проводит проверку базовых функций: создание заказа, изменение и удаление.
- **3.1.4 Демонстрация:**
  - MVP представляется заказчику для обратной связи и оценки.

#### 3.2 Вторая итерация (Функциональные улучшения)

**Цель:** Добавить расширенные функции, такие как отслеживание статуса готовки и уведомления о готовности.

- **3.2.1 Доработка:** На основе обратной связи от первой итерации, корректируются функции.
- **3.2.2 Интеграция с кассовой системой:** Внедрение возможностей для связи с финансовой частью.
- **3.2.3 Тестирование:** Проверка новых функций на разных типах устройств.
- **3.2.4 Презентация:** Оценка заказчиком.

#### 3.3 Третья итерация (Интеграция и оптимизация)

**Цель:** Интеграция с другими системами ресторана, включая CRM и бухгалтерию.

- **3.3.1 Оптимизация:** Улучшение скорости работы приложения.
- \*\*3.3.2 Интеграция с базами данных и настройка панели администратора.
- **3.3.3 Финальное тестирование:** Проведение нагрузочного тестирования и проверка на работоспособность всех бизнес-процессов.

### 4. Внедрение

- **4.1 Релиз:** Публикация приложения для использования в ресторане.
- **4.2 Настройка серверной инфраструктуры:** DevOps настраивает окружение для работы приложения, обеспечивая его стабильность и масштабируемость.

### 5. Поддержка и доработка

- **5.1 Мониторинг:** Постоянное отслеживание работоспособности приложения и фиксация багов.
- **5.2 Улучшения:** Введение новых функций на основе отзывов пользователей и заказчика.

## Оценка времени выполнения задач:

| Этап                  | Время выполнения |
| --------------------- | ---------------- |
| Инициация проекта     | 1-2 недели       |
| Первая итерация (MVP) | 4-6 недель       |
| Вторая итерация       | 3-4 недели       |
| Третья итерация       | 3-4 недели       |
| Внедрение             | 1-2 недели       |
| Поддержка и доработка | 6-8 недель       |

## Оценка стоимости проекта:

| Роль                    | Количество | Время работы         | Стоимость (в т.р.) |
| ----------------------- | ---------- | -------------------- | ------------------ |
| Владелец продукта (PO)  | 1          | Весь проект          | 150                |
| Проектный менеджер (PM) | 1          | Весь проект          | 130                |
| Бизнес-аналитик         | 1          | Весь проект          | 100                |
| Системный аналитик      | 1          | Все время разработки | 90                 |
| Дизайнер                | 1          | ~ 1 мес.             | 80                 |
| Архитектор БД           | 1          | ~ 1 мес.             | 120                |
| Разработчики            | 4          | ~ 3 мес.             | 300                |
| Тестировщики            | 2          | ~ 1 мес.             | 90                 |
| DevOps                  | 1          | ~ 2 недели           | 110                |

**Итого:** Примерная стоимость проекта без учета непредвиденных затрат составит около 1.170.000 руб.
