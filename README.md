# Мессенджер. Фронтенд часть.

## Инструменты

- JS и TS
- деплой на Netlify
- Docker
- полностью свой шаблонизатор
- Chai, Mocha — тесты

## ТЗ

- Экраны приложения
  - Страница авторизации. Есть ссылка на страницу регистрации. Если авторизация прошла успешно либо на эту страницу пытается зайти уже авторизованный пользователь, он попадает на страницу со списком чатов. Если же авторизоваться не получилось, будут выведены одно или несколько сообщений об ошибках.

  - Страница регистрации. **При успешной регистрации происходит редирект пользователя на страницу со списком чатов. Если зарегистрироваться не получилось, в форме появятся сообщения в каких полях данные не прошли валидацию.

  - Страница со списком чатов. Состоит из двух основных блоков: слева — область для списка чатов (без нумерации) с полем ввода для поиска, справа — область чата. Если чат не выбран, необходимо добавить «заглушку». Добавьте также кнопку для перехода в профиль пользователя.

  - Страница с чатом. Два блока: слева — список с чатами, но один из них должен быть активным; справа — блок с «лентой» переписки активного чата. Нужно отображать следующую информацию о сообщениях: дата отдельного сообщения, прочитано ли, дата переписки (например, 19 июля: «лента» сообщений за этот день). Необходимо выделять собеседников (цветом или расположением сообщений), а также само сообщение. Нужно уметь отправлять и отображать: обычный текст, Emoji, картинки, видео.

  - Страница профиля. Содержит информацию о пользователе, которую можно изменить. Обязательные поля: имя, никнейм, почта, телефон, пароль, аватар (возможность загружать новый и удалять текущий). Изменять данные можно на этой же странице. Ниже пример с двумя страницами: просто информация и если пользователь хочет поменять что-то. Вы можете сделать по другому.

  - Страница 404. Страница содержит информацию о том, что пользователь «заблудился» и отображать кнопку для возврата в сервис.

  - Страница 5-ошибок.** Страница содержит вежливый текст, что сервис «сломался», но проблемы уже устраняются.

- Возможности чатов:

  - создание чата;
  - изменение параметров чата: название, аватар, пароль;
  - удаление чата;
  - добавление и удаление пользователей из чата;
  - поиск по всем чатам.

- Возможные действия с сущностью пользователя:

  - регистрация;
  - авторизация;
  - изменение данных;
  - добавить аватар;
  - выйти из аккаунта;