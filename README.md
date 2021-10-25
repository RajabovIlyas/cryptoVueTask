# task-crypto-website
####Технологии:

Vue.js, Redux/Vuex, Bootstrap, SCSS, БЭМ, плюсом будет TS.

####API: Coincap

Main:

На главной отображается список (таблица) криптовалют с основной информацией по ним и с контролами для возможности добавления в портфель (например, "+".). Реализовать пагинацию.

При нажатии на элемент таблицы, открывается страница с подробной информацией по валюте, с контролом для добавления в портфель, а также ее история в виде графика (можно использовать либы для визуализации данных).

При нажатии на "+", открывается модальное окно, где можно ввести количество (в т.ч. дробное) криптовалюты. После сабмита, криптовалюта добавляется в портфель в указанном количестве.

Реализовать роутинг. Кнопка "Вернуться" браузера должна работать корректно.

####Header:

Стоимость 3 популярных криптовалют в ряд. Стоимость портфеля пользователя и разница с изначальной стоимостью портфеля, в скобках разница в процентах. Example: 134,32 USD +2,38 (1,80 %). При обновлении портфеля мы храним инфо о стоимости добавленной валюты на момент обновления. При следующем запуске (релоаде) приложения мы получаем текущие стоимости валют и можем обновить разницу.

При нажатии на информацию о портфеле, открывается модальное окно со списком валют в портфеле и возможностью убрать каждую из них из портфеля.

Портфель должен быть устойчив к релоду страницы (localStorage).

Дизайн должен быть простым, понятным и функциональным.

####Таймлайн:

день 1:

Создать UI приложения (компоненты, кнопки, меню).

день 2:

Добавить редакс стор, написать необходимые экшоны для обращения к API.

день 3-4:

Добавить редюсеры, связать стор с UI, добавить навигацию если еще нет.

## Project setup
```
yarn install
```

### Compiles and hot-reloads for development
```
yarn serve
```

### Compiles and minifies for production
```
yarn build
```

