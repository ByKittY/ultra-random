# ultra-random

Rastgele şifre üret.

## Install
```js
npm install ultra-random
```

## Örnek

 
```js
const random = require('ultra-random');

random(4);   // 'WA6n'

random(10);   // '49Pm!N&i9M'
```

Şifre oluşturmak için kullanılacak harfleri ve uzunluğunu belirleyin:
random(uzunluk, 'harfler') Şeklinde
```js

random(4, '1234567890');  // '5575'

random(10, '1234567890'); // '1926972366'

```

Eğer büyüklük `Nan`, `Infinity` veya `-Infinity`, ise doğal uzunluk `8` eğer kullanılırsa:
```js
random(NaN);  //'0vpgip!G'
```


-
