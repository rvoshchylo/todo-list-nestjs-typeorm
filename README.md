# Todo List

Це простий додаток для списку справ, побудований за допомогою NestJS, TypeORM, PostgreSQL та Docker.

## Використані технології
- **NestJS**: Прогресивний фреймворк Node.js для побудови ефективних, надійних та масштабованих серверних додатків.
- **TypeORM**: ORM, який може працювати на платформах NodeJS, Browser, Cordova, PhoneGap, Ionic, React Native, NativeScript, Expo та Electron.
- **PostgreSQL**: Могутній, відкритий об'єктно-реляційний система управління базами даних.
- **React**: Бібліотека для створення інтерфейсів користувача, яка дозволяє розробникам будувати високопродуктивні UI-компоненти.
- **Docker**: Платформа для розробки, доставки та виконання програмного забезпечення за допомогою контейнеризації. Дозволяє упаковувати програми та їх залежності в контейнери для легкого розгортання та керування середовищами розробки та виробництва.

## Особливості
- **Створення задач**: Користувачі можуть створювати нові задачі з назвою.
- **Оновлення задач**: Користувачі можуть оновлювати існуючі задачі, включаючи позначення задач як завершені та у процесі.
- **Видалення задач**: Користувачі можуть видаляти непотрібні задачі.
- **Фільтрація задач**: Користувачі можуть фільтрувати задачі за статусом.

## Встановлення та налаштування
1. Склонуйте репозиторій на ваш комп'ютер.
2. Перейдіть до директорії проекту.
3. Встановіть залежності, виконавши команду `npm install`.

### Запуск сервера:

1. Відкрийте термінал.
2. Перейдіть до директорії, де знаходиться ваш серверний код.
3. Відкрийте термінал і створіть .env файл командою `npm run start:env`
4. Відкрийте новий термінал і запустіть docker-container командою `docker-compose up --build`
5. Запустіть сервер, виконавши команду запуску `npm start`.

### Запуск клієнта:

1. Відкрийте новий термінал або закрийте термінал сервера та відкрийте новий.
2. Перейдіть до директорії з клієнтським кодом.
3. Запустіть клієнтський додаток, виконавши команду запуску, яка зазвичай є `npm start`.

### Перевірка роботи програми:

1. Після того, як обидва додатки успішно запущено, відкрийте веб-браузер.
2. Перейдіть на адресу, де працює ваш клієнтський додаток.
3. Переконайтеся, що клієнтська частина програми відображається і взаємодіє з сервером так, як ви очікуєте.

## Автори
- [Ruslan Voshchylo](https://github.com/rvoshchylo)
