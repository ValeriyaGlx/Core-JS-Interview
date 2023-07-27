# Вопросы CoreJS

## ТИПЫ ДАННЫХ:

- [Перечислите все типы данных](topics/types/types.md)
- [Как узнать какой тип данных перед нами?](topics/types/typeof.md#typeof)
- [Почему typeof null === 'object'?](topics/types/typeof.md#typeofnull)
- [Почему typeof function() {} === 'function'?](topics/types/typeof.md#typeoffunc)
- [В чем их разница между null и undefined?](topics/types/typeof.md#null-undefined)
- [Как создать объект? (три способа)](topics/types/typeof.md#obj)
- [Что такое NaN? typeof NaN.](topics/types/typeofNaN.md#typeofnan)
- [NaN === NaN ? Почему?](topics/types/typeofNaN.md#naneqvelnan)
- [Тогда как узнать что перед нами NaN?](topics/types/typeofNaN.md#isnan)
- [Что такое Infinity?](topics/types/typeofInfinity.md#typeofinfinity)
- [isFinite() что это за функция?](topics/types/typeofInfinity.md#isfinite)
- [0.1 + 0.2 === 0.3 ? Почему?](topics/types/number.md#loss-of-accuracy)
- [Числовые методы приведения строки в число.](topics/types/number.md#number-methods)
- [Можем ли к числу применять .toString(). Какая у этого метода особенность?](topics/types/number.md#number-tostring)
- [Что такое Math? Приведите примеры.](topics/types/number.md#math-obj)
- [Mетоды строк. Как получить подстроку.](topics/types/string.md#string-methods)
- [Что будет в консоли и почему:](topics/types/string.md#immutability)
  ```JS
  let str = "Привет!"
  str[0]= "п"
  console.log(str)
  ```
- [Что такое шаблонные строки? Перечисли особенности.](topics/types/string.md#template)
- [Что такое конкатенация?](topics/types/string.md#concatenation)
- [Что такое регулярные выражения? Метод для работы с ними. Приведите примеры.](topics/types/string.md#regex)
  
#### ПРИВЕДЕНИЕ ТИПОВ ДАННЫХ

- [Какие типы данных можно привести? Как? Явно и неявно.](topics/types/dataTypeReduction.md)
   
## ОПЕРАТОРЫ:

- [Перечислите операторы сравнения](topics/operators/operators.md#compare)
- [Разница между `==` и `===`](topics/operators/operators.md#strict-and-lax)
- [Перечислите логические операторы](topics/operators/operators.md#logical)   
- [Что такое оператор нулевого слияния?](topics/operators/operators.md#zero-merge)
- [В чем разница ?? с логическим ИЛИ](topics/operators/operators.md#merge-logical)
- [Перечислите falsy values](topics/operators/operators.md#falsy-values)
- [Важные моменты при работе с операторами сравнения:](topics/operators/operators.md#important)
- [К чему приводятся null и undefined при использовании математических операторов и операторов сравнения.](topics/operators/operators.md#null-undefined)
- [Swich case конструкция, что это для чего что заменяет?](topics/operators/swichCase.md#swich-case)
- [Обязателен ли default? A break?](topics/operators/swichCase.md#default-break) 
- [Что такое тернарный оператор? Почему он называется тернарный?](topics/operators/otherOperators.md#ternary) 
- [Может ли мы создавать цепочку из тернарных операторов?](topics/operators/otherOperators.md#ternary-chain) 
- [Что такое оператор запятая?](topics/operators/otherOperators.md#comma) 
- [Что такое оператор расширения (разворота)? spread-оператор](topics/operators/otherOperators.md#spread) 
- [JS операторы spread vs rest](topics/operators/otherOperators.md#spread-vs-rest) 

## ПЕРЕМЕННЫЕ, ХОИСТИНГ
- [Как можно объявить переменную?](topics/variables/variables.md#var-let-const)
- [Что такое переменная?](topics/variables/variables.md#variable)
- [Разница между let, var и const](topics/variables/variables.md#difference)
- [Что такое хоистинг?](topics/variables/variables.md#hoisting)
- [Какие функции всплывают?](topics/variables/variables.md#func-hoisting)
- [Что будет если](topics/variables/variables.md#var-a)
  ```JS
	 console.log(a)
	 var a = 5;
	```
- [А если var заменить на let что измениться?](topics/variables/variables.md#let-a)
- [Что такое временная мертвая зона и зачем она нужна?](topics/variables/variables.md#tdz)
- [Почему var обладают хоистингом](topics/variables/variables.md#var-hoisting)
- [Что такое полифиллы. Приведи пример.](topics/variables/variables.md#polyfill)

## ФУНКЦИИ:

- [Что такое функциональное программирование](topics/functions/functions.md#func-prog)
- [Какие виды функций вы знаете. Какие различия?](topics/functions/functions.md#functions)
- [Какие особенности у стрелочной функции?](topics/functions/functions.md#arrow-func)
- [Что такое callback функция?](topics/functions/functions.md#callback)
- [Что такое функция высшего порядка?](topics/functions/functions.md#higher-order)
- [Что такое чистая функция?](topics/functions/functions.md#clean-func)
- [Что такое iife? Для чего она нужна?](topics/functions/functions.md#iife)
- [Что такое функция конструктор?](topics/functions/functions.md#constructor)
- [Что такое замыкание?](topics/functions/functions.md#closure)
- [Что такое new?](topics/functions/functions.md#new)
- [Что такое this?](topics/functions/functions.md#this)
- [Можем ли мы привязаться this к функции? Какие методы?](topics/functions/functions.md#this-func)
- [Особенности bind.](topics/functions/functions.md#bind)

## OOP
- [Что такое OOP?](topics/OOP/OOP.md#oop)
- [Что такое инкапсуляция?](topics/OOP/OOP.md#encapsulation)
- [Что такое наследование?](topics/OOP/OOP.md#inheritance)
- [Что такое полиморфизм?](topics/OOP/OOP.md#polymorphism)
- [Что такое ассоциация?](topics/OOP/OOP.md#association)
- [Что такое композиция?](topics/OOP/OOP.md#composition)
- [Что такое агрегация?](topics/OOP/OOP.md#aggregation)
- [Что такое абстрактный класс?](topics/OOP/OOP.md#abstract-class)
- [Что такое интерфейс?](topics/OOP/OOP.md#interface)
- [Что такое абстрактный метод?](topics/OOP/OOP.md#abstract-method)
- [Что такое статический метод?](topics/OOP/OOP.md#static-method)
- [Что такое статическое свойство?](topics/OOP/OOP.md#static-prop)
- [Что такое инстанс и инстанцирование?](topics/OOP/OOP.md#instance)
- [Что такое декоратор?](topics/OOP/OOP.md#decorator)
- [Что такое декоратор класса?](topics/OOP/OOP.md#class-decorator)
- [Что такое декоратор метода?](topics/OOP/OOP.md#method-decorator)
- [Что такое декоратор свойства?](topics/OOP/OOP.md#prop-decorator)
- [Что такое декоратор параметра?](topics/OOP/OOP.md#param-decorator)
- [Что такое декоратор геттера и сеттера?](topics/OOP/OOP.md#get-set-decorator)
- [Что такое декоратор функции?](topics/OOP/OOP.md#func-decorator)
  
## ОБЪЕКТЫ

- [Создать объект через Object.create.](topics/objects/objects.md#obj-create)
- [Дескрипторы свойств объекта.](topics/objects/objects.md#descriptors)
- [Как копировать объект. Глубоко и нет. Нюансы JSON.stringify.](topics/objects/objects.md#copy-obj)
- [Перечисли встроенные методы объекта, для получения ключей, значений, и ещё один похожий метод.](topics/objects/objects.md#keys-values)
- [Что такое Map и Set? Чем Map отличается от объекта.](topics/objects/objects.md#map-set)
- [Что делает метод Object.is?](topics/objects/objects.md#obj-is)
- [Что делают методы Object.freeze() и Object.seal()?](topics/objects/objects.md#freeze)

## МАССИВЫ

- что такое массив, как создать, несколько способов, как копировать.
- Как копиро вать честь массива.
- Как сгладить вложенный массив
- разница map и forEach
- reduce что делает, что принимает вторым аргументом
- filter что делает
- какие методы изменяют исходный массив
- можем ли мы изменять массив и объект после объявления через co  nst. Почему?

## ЦИКЛЫ

- [Перечислите все циклы](topics/cycles/cycles.md#cycles)
- [For...in для чего](topics/cycles/cycles.md#for-in)
- [For...of для чего](topics/cycles/cycles.md#for-of)
- [Можно ли применить for...in для массива. Что будет?](topics/cycles/cycles.md#for-in-arr)
- [Можно ли применить for...of или while для объекта? Что будет?](topics/cycles/cycles.md#for-of-obj)
- [Цикл do...while что делает?](topics/cycles/cycles.md#do-while)
- [Break и continue что это и для чего?](topics/cycles/cycles.md#break-continue)

## БРAУЗЕР

- [Что такое DOM?](topics/browser/browser.md#dom)
- [Что такое document?](topics/browser/browser.md#document)
- [Что такое BOM?](topics/browser/browser.md#bom)
- [Что такое CSSOM?](topics/browser/browser.md#cssom)
- [Поиск элементов в DOM](topics/browser/browser.md#dom-serch)
- [Живые и неживые коллекции что это?](topics/browser/browser.md#collections)
- [Браузерные события](topics/browser/browser.md#events)
- [Фазы события](topics/browser/browser.md#phases)
- [Обработчик событий, как повесить, как убрать. Какой нюанс, если мы хотим удалить обработчик](topics/browser/browser.md#event-listeners)
- [Еvent.preventDefault() что это что делает](topics/browser/browser.md#prevent-default)
- [Как предотвратить распространение события](topics/browser/browser.md#stop-propagandation)
- [Что такое делегирования событий](topics/browser/browser.md#delegate)

## АСИНХРОННОСТЬ

- [Что такое синхронный код?](topics/async/async.md#sync)
- [Что такое асинхронный код?](topics/async/async.md#async)
- [Что такое event loop?](topics/async/async.md#event-loop)
- [Что такое коллбеки?](topics/async/async.md#callback)
- [Что такое промисы?](topics/async/async.md#promise)
- [Что такое async await?](topics/async/async.md#async-await)
- [Что такое микро и макро задачи?](topics/async/async.md#micro-task)

## ОБЩЕЕ

- что такое стек вызовов
- что такое очередь задач
- что такое мемоизация
- что такое рекурсия
- что такое чистая функция
- что такое побочный эффект
- что такое мутация
- что такое иммутабельность
- что такое декларативный код
- что такое императивный код
- что такое SOLID, DRY, KISS, YAGNI
- что такое TDD
- что такое BDD
- что такое DDD
- что такое Feature sliced design
- что такое MVC
- что такое MVVM
- что такое MVP
- что такое SPA
- что такое SSR
- что такое CSR
- что такое PWA
- что такое SSR
- что такое антипаттерны
- что такое рефакторинг
- что такое абстракция
