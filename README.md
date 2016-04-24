# Задание 1 — Телепрограмма

Для того чтобы полностью реализовать этот проект, мне пришлось поднять сервер, который будет парсить сайт http://www.programma.tv/
Таким у меня появился доступ к расписанию передач каждого канала.

Концепцию работы сервера вы можете посмотреть вот тут https://github.com/fletcherist/task1server

Я использовал концепцию React + Redux для фетчинга и отображения данных.
За основу я использовал бойлерплейт от * davezuko/react-redux-starter-kit * https://github.com/davezuko/react-redux-starter-kit
потому что он мне очень знаком, и я знаю, как с ним обращаться.

#### Вся работа находится в `./src/components`
#### Фетчинг редьюсеры в `./src/redux/modules`

Компонентный подход оказался очень кстати при реализации одинаковых частей интерфейса приложения, таких как, например, телеканалов, или заголовков телепередач.
Вы можете с лёгкостью поднять проект у себя на компьютере, форкнув репозиторий, и затем:
### `npm start`
