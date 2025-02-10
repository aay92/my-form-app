Form Capture App
Описание
Это веб-приложение для создания задач через форму захвата. Приложение разработано с использованием Next.js , Vite , Tailwind CSS . Форма отправляет данные на сервер через API и показывает пользователю результат выполнения запроса.

Функциональность
Создание задачи : Пользователь может заполнить форму с параметрами задачи (название, описание, бюджет, теги и т.д.).
Отправка данных на сервер : Данные из формы отправляются на сервер через POST-запрос.
Уведомления : После отправки формы пользователь получает уведомление об успехе или ошибке.
Сохранение токена : Токен авторизации сохраняется между сессиями с помощью localStorage.
Стек технологий
Frontend : Next.js, Vite, Tailwind CSS
HTTP-клиент : Axios (или Fetch API)
Хостинг : Vercel
