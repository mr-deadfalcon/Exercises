### Задача 1. Вывод сообщения в консоль.
Выведите в консоль сообщение "Я JavaScript!"
```javascript
console.log('Я JavaScript!');
```

### Задача 2. Копирование переменной.
Объявите две переменные: admin и user.  
Запишите строку "Tom" в переменную admin.  
Скопируйте значение из переменной admin в переменную user.  
Выведите на консоль значение user, (должно вывести "Tom").

```javascript
let admin;
let user;

admin = 'Tom';
user = admin;

console.log(user);
```

### Задача 3. Тип переменной.
Объявите переменные следующих примитивных типов:
* Number
* String
* Boolen
* null  

Выведие в консоль тип каждой переменной.

```Javascript
let n = 1;
let s = '1';
let b = true;
let nl = null;

console.log(typeof(n),typeof(s),typeof(b),typeof(nl));
```

### Задача 4. Шаблонные строки.
Обявите переменную содердающую ваш возраст. Например: 42. 
Выведит в консоль фразу "Мой возраст - 42 года" используя обратные кавычки.

```Javascript
let age = 42;
console.log(`Мой возраст - ${age} года`);
```
















