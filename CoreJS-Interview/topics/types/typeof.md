# <a id="typeof" />Как узнать какой типа данных перед нами?
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
# <a id="typeofnull" />Почему typeof null === 'object'?
 Это официально признанная ошибка в языке, которая сохраняется для совместимости.   
 На самом деле null – это не объект, а отдельный тип данных.


# <a id="typeoffunc" />Почему typeof function() {} === 'function'?

Функции не являются отдельным базовым типом в JavaScript, а подвидом объектов.     
Но typeof выделяет функции отдельно, возвращая для них "function". На практике это весьма удобно, так как позволяет легко определить функцию.

# <a id="null-undefined" />В чем их разница между null и undefined?

undefined - получается при попытке получить значение там, где значения нет.    
null — явное «зануливание» переменной (object = null), когда ссылка на объект больше не требуется.   
Упрощённо: JavaScript использует undefined, а программисты должны использовать null.

# <a id="obj" />Как создать объект? (Три способа)

1. С использованием литерального синтаксиса: const person = {};
2. С использованием ключевого слова «new»: const person = new Object();
3. Использовать метод Object.create(proto, properties) - где
    proto - oбъект, который должен быть прототипом вновь созданного объекта,
    properties - необязательный, можно указать дескртипторы свойст объекта - [настройки конфигурации объекта](https://learn.javascript.ru/property-descriptors)
