Данный проект был разделен мной на следующие модули:

1. Микрофронт авторизации. В него входит логика связанная с авторизацией и регистрацией пользователя

2. Микрофронт мест. В него входит логика отвечяающая за добавление мест, их отображение и просмотр

3. Микрофронт профиля пользователя. В нем реализована логика работы с аккаунтом пользователя.  

<h3> Микрофронт авторизации </h3>

В данный микрофронт были вынесены компоненты "[Login.js](microfrontend/auth_microfrontend/components/Login.js)" и "[Register.js](microfrontend/auth_microfrontend/components/Register.js)", а так же файлы связанные с ними файлы css и auth.js, где хранятся методы обращения по апи.

<h3> Микрофронт мест </h3>

В данный микрофронт были вынесены компоненты "[AddPlacePopup.js](microfrontend/place_microfrontend/components/AddPlacePopup.js)", "[Card.js](microfrontend/place_microfrontend/components/Card.js)" и "[ImagePopup.js](microfrontend/place_microfrontend/components/ImagePopup.js)", а так же файлы связанные с ними файлы css и api.js, где хранятся методы обращения по апи.

<h3> Микрофронт профиля пользователя </h3>

В данный микрофронт были вынесены компоненты "[EditAvatarPopup.js](microfrontend/profile_microfrontend/components/EditAvatarPopup.js)" и "[EditProfilePopup.js](microfrontend/profile_microfrontend/components/EditProfilePopup.js)" , а так же файлы связанные с ними файлы css и api.js, где хранятся методы обращения по апи.




## Для запуска приложения

First, run the development server:

```bash
npm i
# or
yarn start

```

Откройте [http://localhost:3000](http://localhost:3000) в браузере для запуска приложения.