# <a id="typeofinfinity" />Что такое Infinity?

Infinity является числовым значением, представляющим математическую бесконечность и сохраняет его поведение.

```JS
typeof Infinity === "number"
console.log(Infinity + 1); // Infinity
console.log(Math.pow(10, 1000)); // Infinity
console.log(Math.log(0)); // -Infinity
console.log(1 / Infinity); // 0
```

# <a id="isfinite" />isFinite() что это за функция?

  Oпределяет, является ли переданное значение конечным числом. Если необходимо, параметр сначала преобразуется в число.

  ```JS
  isFinite(Infinity); // false
  isFinite(NaN); // false
  isFinite(-Infinity); // false

  isFinite(0); // true
  isFinite(2e64); // true

  ```
