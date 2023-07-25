# Как узнать какой типа данных перед нами?
<a name="typeof"></a> 

  Оператор typeof возвращает тип аргумента. Унарный оператор typeof возвращает строку, указывающую тип необязательного
  операнда. Пример:

  ```JS
  typeof 42 === 'number'
  typeof 'blabla' === 'string'
  typeof undefined === 'undefined'
  typeof true === 'boolean'
  typeof {a: 1} === 'object'
  typeof Symbol() === 'symbol'
  typeof null === 'object'
  typeof function() {} === 'function'
  ```
