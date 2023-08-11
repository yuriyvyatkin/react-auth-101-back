## Аутентификация пользователя

**🛠️ Стек**

Express.js + MongoDB

**💬 Основная информация о проекте**

Backend часть приложения на основе LinkedIn курса "React: Authentication":
https://www.linkedin.com/learning/react-authentication/

Основные возможности приложения:
* аутентификация на базе JWT токена;
* вход при помощи Google аккаунта;
* верификация почты;
* сброс пароля;
* шифрование пароля;
* обработка ошибок;
* защита БД.

Frontend часть приложения: https://github.com/yuriyvyatkin/react-auth-101-front

**📚 Инструкция по запуску**

##### 1. Клонирование

```
git clone https://github.com/yuriyvyatkin/react-auth-101-back.git
```

```
cd react-auth-101-back
```

##### 2. Установка MongoDB

Скачать MongoDB версии 6.0.8 для своей системы по ссылке https://www.mongodb.com/try/download/community и установить с настройками по умолчанию. Перезагрузить систему, если служба MongoDB не запустилась сразу.

##### 3. Запуск

```
npm i && npm run start
```

или

```
npm install
```

```
npm run start
```
