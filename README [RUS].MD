# angular-rating-stars
Довольно неплохой плагин для создания рейтинга из звезд.

##Как использовать:

Для начала добавьте в свое приложение шрифт font-awesome

(файл **"_icons.fontawesome.min.css"** и папку **"fonts-icons"**)

Дальше вставьте директиву **"ngStars"** из файла **"js/angular-app.js"**

И сразу после этого можете использовать данный модуль!

####Простой пример (можно изменять рейтинг кликом на звезду)
```html
  <div ng-stars="SCOPE_ПЕРЕМЕННАЯ"></div>
```

####Пример, где нельзя менять рейтинг кликом
```html
  <div ng-stars="SCOPE_ПЕРЕМЕННАЯ" ng-stars-readonly></div>
```

####Пример с произвольным количеством звезд
```html
  <div ng-stars="SCOPE_ПЕРЕМЕННАЯ" ng-stars-max="10"></div>
```

####Пример с вызовом callback только при первом изменении рейтинга
**ВАЖНО:** Callback функция должна возвращать TRUE или FALE. Если функция вернет TRUE - функция будет выполняться при каждом изменении рейтинга. Если вернется FALSE - callback функция сработает только при первом изменении рейтинга.
```html
  <div ng-stars="SCOPE_VAR" ng-stars-callback="CALLBACK_FUNCTION"></div>
```

####Пример с вызовом callback при каждом изменении рейтинга
**ВАЖНО:** Callback функция должна возвращать TRUE или FALE. Если функция вернет TRUE - функция будет выполняться при каждом изменении рейтинга. Если вернется FALSE - callback функция сработает только при первом изменении рейтинга.
```html
  <div ng-stars="SCOPE_VAR" ng-stars-callback="CALLBACK_FUNCTION"></div>
```

((Все эти примеры вы можете найти в файле index.html))
