# Ссылка https://sdntmn.github.io/task-frontend/

#  Вакансия :: Frontend-разработчик

Разработка бизнес-системы с использованием веб-технологий. Автоматизация сервисов с большим количеством пользователей.

## От вас

### Обязательно

- Знание синтаксиса языков JavaScript, TypeScript
- Базовые знания принципов работы Web
- Желание работать в команде и развиваться

### Приветствуется

- Навыки работы с React, Redux, MobX
- Опыт работы с WebSocket
- Опыт работы с ОС семейства GNU Linux
- Работа с системами управления исходным кодом Git
- Знания базовых принципов разработки (тестирование, рефакторинг, Code Review)

### Будет круто, но не обязательно

- Знание английского языка на уровне чтения технической документации;
- Участие в разработке Open Source проектов;
- Наличие профиля на GitHub, Stack Overflow;
- Наличие проектов которые можете продемонстрировать.

## У нас

- Полный рабочий день, гибкий обед по желанию сотрудника, гибкое время начала рабочего дня;
- Полностью «белая» заработная плата с возможностью увеличения в процессе работы (зависит от отдачи сотрудника)
- Добровольное медицинское страхование
- Дружелюбная команда с юмором, готовая поддержать
- Интересный проект и необычные задачи. Нет, если думаете, что рутины нет, она есть, но нацелены мы именно на продуктив
- Возможность одновременно участвовать в разных проектах и развивать другие компетенции
- Возможность попробовать современные тренды и практики в разработке ПО
- По желанию: один день в неделю - удаленная работа
- Никаких опенспейсов, а комфортное пространство в центре Тюмени
- Готовы безгранично делиться опытом при условии, что вы готовы принимать

Если у вас есть опыт работы с 1С, то эта вакансия не для вас. Даже не пытайтесь. Если вакансия вас заинтересовала, но есть какие-то недопонимания и вопросы, приходите, обсудим, договоримся.
Большим плюсом будет выполнение тестового задания. Решение принимается в виде PR к текущему репозиторию

## Тестовое задание

Создайте форму обратной связи.
В форме пользователь может:

- ввести имя
- ввести фамилию
- ввести email
- выбрать категорию сообщения
- написать сообщение
- добавить картинку

Дополнительно необходима валидация по следющим правилам:

- email - обязательное поле
- имя, фамилия - должно быть заполнено одно из двух
- категория - выпадающий список. Поле обязательное, но значение по умолчанию должно быть пустым. Пустое значение не принимается
- сообщение - обязательное, минимум 10 символов
- картинка - формат jpg, png. Размер не более 2Мб

Результат заполнения фоормы должен быть в формате JSON для отправки в API

### Условия

- использовать React js
- писать на TypeScript (не обязательно, но будет огромным плюсом)
- форма должна быть адаптивной
- придерживаться методологии БЭМ
- все должно происходить в браузере без использования стороннего сервера
