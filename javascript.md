!SLIDE center

# Javascript

!SLIDE

# Javascript

* Runs in browser
* Much alike Ruby (in some aspects)
* ECMAScript (Actionscript)
* Events
* AJAX

!SLIDE

# DataTypes

```javascript
num = 2013;
fl  = 2.0;
str = 'The Next Web';

alert(str + ', ' + num);
```

```javascript
arr = new Array(); // arr = []
arr.push('Raymond van Dongelen');
arr.push('Sjef Smeets');
```

```javascript
obj = new Object(); // obj = {}
obj.teacher1 = 'Jan-Wessel Hovingh';
obj.teacher2 = 'Guido Swildens';
```

!SLIDE execute smbullets bullets

# jQuery

* A very popular Javascript-Framework
* Easy AJAX
* Easy Access to the DOM
* Browser-agnostic

```javascript
$('title').html('Hello from the slides!');
$('.execute h1').html();
```

```javascript
$.get('/', function(data) {
  alert(data);
})
```

!SLIDE

# Node.js

* A server-side framework
* I will not talk about this today