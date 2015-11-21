angular-jquery-maskedinput
==========================

digitalBush/jquery.maskedinput (https://github.com/digitalBush/jquery.maskedinput) to AngularJS

### Scripts

```html
<script type="text/javascript" src="//cdn.jsdelivr.net/jquery.maskedinput/1.3.1/jquery.maskedinput.min.js"></script>
<script src="scripts/angular-jquery-maskedinput.js"></script>
```

### App

```js
var app = angular.module('YourApp', ['angular-jquery-maskedinput']);
```

### View

```html
<input type="text" id="Creation_Date" name="Creation_Date" maxlength="50" class="form-control" data-ng-model="event.date" mask data-mask="99/99/9999" />
```

### Directive Info

You can use:

data-mask

data-mask-placeholder (optative)

More information in https://github.com/digitalBush/jquery.maskedinput

### Bower

https://libraries.io/bower/angular-jquery-maskedinput
