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
# Почему typeof null === 'object'?
<a name="null-object"></a> 

 Это официально признанная ошибка в языке, которая сохраняется для совместимости. На самом деле null – это не объект, а отдельный тип данных.

 # Почему typeof function() {} === 'function'?
 <a name="typeof-function"></a> 

Функции не являются отдельным базовым типом в JavaScript, а подвидом объектов.   
Но typeof выделяет функции отдельно, возвращая для них "function". На практике это весьма удобно, так как позволяет легко определить функцию.
 
# В чем их разница между null и undefined?
<a name="null-undefined"></a> 

undefined - получается при попытке получить значение там, где значения нет.   
null — явное «зануливание» переменной (object = null), когда ссылка на объект больше не требуется.
 
