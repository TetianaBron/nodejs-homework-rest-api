# Работа с контактами

## Роуты

http://localhost:3000/api/contacts - get - показать все контакты
http://localhost:3000/api/contacts - post - добавить контакт (поля name, email, phone - обязательны, favorite - опционально)
http://localhost:3000/api/contacts/id - get - получить контакт по ID
http://localhost:3000/api/contacts/id - put - обновить контакт (хотя бы одно поле должно быть обновлено)
http://localhost:3000/api/contacts/id - delete - удалить контакт
http://localhost:3000/api/contacts/id/favorite - patch - обновить поле 'favorite'

(есть валидация)

### Команды:

- `npm start` &mdash; старт сервера в режиме production
- `npm run start:dev` &mdash; старт сервера в режиме разработки (development)
- `npm run lint` &mdash; запустить выполнение проверки кода с eslint
- `npm lint:fix` &mdash; та же проверка линтера, но с автоматическими исправлениями простых ошибок

#### работа с Mongoose, Joi
