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

##### 1. Клонировать репозиторий и перейти в папку с проектом

```
git clone https://github.com/yuriyvyatkin/react-auth-101-back.git
```

```
cd react-auth-101-back
```

##### 2. Установить (если не установлен) и запустить MongoDB

Скачать MongoDB версии 6.0.8 для своей системы по ссылке https://www.mongodb.com/try/download/community и установить с настройками по умолчанию. Перезагрузить систему, если служба MongoDB не запустилась сразу.

##### 3. Создать файл .env в корне проекта со следующими переменными и присвоить им соответствующие значения

```
JWT_SECRET=
SENDGRID_API_KEY=

GOOGLE_CLIENT_ID=
GOOGLE_CLIENT_SECRET=

AWS_USER_POOL_ID=
AWS_CLIENT_ID=
AWS_IDENTITY_POOL_ID=
AWS_REGION=

PEPPER_STRING=
```

##### 4. Запустить проект

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
