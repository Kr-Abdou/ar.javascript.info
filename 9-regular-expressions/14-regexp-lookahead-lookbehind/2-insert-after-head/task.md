# أدخل بعد المقدمة

لدينا سلسلة مع مستند HTML.

اكتب تعبيرًا عاديًا يُدرج `<h1> مرحبًا </ h1>` مباشرة بعد علامة `<body>`. قد يكون للسمات سمات.

على سبيل المثال:

```js
let regexp = /your regular expression/;

let str = `
<html>
  <body style="height: 200px">
  ...
  </body>
</html>
`;

str = str.replace(regexp, `<h1>Hello</h1>`);
```

<<<<<<< HEAD
بعد هذا من المفترض أن تصبح قيمة `str`: 
=======
After that the value of `str` should be:

>>>>>>> 1ce5644a15ee141fbe78c0fb79c8f40d870d7043
```html
<html>
  <body style="height: 200px"><h1>Hello</h1>
  ...
  </body>
</html>
```
