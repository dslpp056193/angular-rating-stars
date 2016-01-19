# angular-rating-stars
Very nice rating plugin with stars. 

##How to use:

Begin add to your app font-awesome styles.

(**"_icons.fontawesome.min.css"** and folder **"fonts-icons"**)

Next include **"ngStars"** directive from **"js/angular-app.js"**

And you can use my module!

####Simple example (you can click on star to change rating)
```html
  <div ng-stars="SCOPE_VAR"></div>
```

####Example with readonly stars
```html
  <div ng-stars="SCOPE_VAR" ng-stars-readonly></div>
```

####Example with custom stars quantity
```html
  <div ng-stars="SCOPE_VAR" ng-stars-max="10"></div>
```


((All this examples you can find in index.html))
