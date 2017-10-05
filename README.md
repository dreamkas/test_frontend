[![Dreamkas](http://static.dreamkas.ru/git_logo.png)](https://dreamkas.ru)

# Front-end разработчик

Присоединяйтесь к “Дримкас”, и у вас появится возможность прокачать навыки работы с новыми технологиями!

Вместе с командой вы будете выбирать и внедрять технологии для проектов, создавать новые фичи и оптимизировать старые, вы сможете непосредственно влиять на развитие продукта.

Проекты все свои, интересные и долгосрочные, много задач-челенджей, и всяких интеграций с внешними API.

Ваш опыт не особо важен, мы с удовольствием поделимся знаниями.

Если вам интересно, то предлагаем выполнить тестовое задание (ниже), чтобы мы могли примерно оценить ваш уровень. Задача простая, поэтому особое внимание мы уделим качеству кода. Ссылки на ваш репозиторий с выполненным заданием отправляйте на [a.gnedovskiy@dreamkas.ru](mailto:a.gnedovskiy@dreamkas.ru).

## Тестовое задание
Реализовать клиентское приложение «Бронирование комнат». Макеты расположены в каталоге /design. Ниже описан требуемый функционал.

### Первый экран
Пользователю отображается список комнат. Данные о комнатах подгружаются с сервера по API. Информация о каждой комнате включает в себя номер и имя забронировавшего комнату. Если комната свободна вместо имени ставится прочерк.

На первом экране возможно отфильтровать список комнат. Доступные фильтры:

* Все комнаты
* Только свободные комнаты
* Только забронированные комнаты

По клику на одну из комнат списка – пользователь переходит на страницу бронирования комнаты.

### Экран бронирования
Пользователю отображается заголовок с номером комнаты.

Рядом с заголовком есть кнопка «назад» по клику на которую пользователь попадает обратно в список комнат.

Под заголовком отображается поле ввода имени (на кого забронирована комната). Если поле оставить пустым, то комната считается свободной.

По клику на кнопке сохранить данные о бронирование отправляются на сервер. После успешного сохранения пользователь попадает на страницу со списком комнат, где видит данные с учетом последнего редактирования.

## Условия выполнения
1. Для выполнения задания использовать одну из следующих связок:
  * AngularJS + Angular Material
  * React + Material-UI
2. Верстка должна:
  * Соответствовать макетам
  * Корректно отображаться в последних версиях популярных браузеров
  * Быть адаптивной, мобильная версия от 320px до 600px
3. Желательно использовать flexbox при верстке

## Запуск тестового сервера

Для запуска локального сервера понадобится установить Node.js последней стабильной версии. После установки Node.js перейдите в папку проекта и выполните следующие шаги:

* Установите npm-пакеты проекта:
```
npm install
```
* Установите пакет gulp-cli глобально:
```
npm install -g gulp-cli
```
* Запустите тестовый сервер:
```
gulp server
```

По адресу  [localhost:3000/api/rooms/](http://localhost:3000/api/rooms/)
доступны данные по комнатам для бронирования.

**Удачи!**
