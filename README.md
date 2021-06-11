# Типы данных 
https://developer.mozilla.org/ru/docs/Web/JavaScript/Data_structures
# Стандартные встроенные объекты
https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Global_Objects
# JavaScript
https://developer.mozilla.org/ru/docs/Web/JavaScript
# Начало работы с Вебом
https://developer.mozilla.org/ru/docs/Learn/Getting_started_with_the_web



6 типов данных являющихся примитивами:
1)        Undefined (Неопределённый тип)  : typeof instance === "undefined"
2)        Boolean (Булев, Логический тип) : typeof instance === "boolean"
3)        Number (Число) : typeof instance === "number"
4)        String (Строка) : typeof instance === "string"
5)        BigInt  : typeof instance === "bigint"
6)        Symbol (в ECMAScript 6)  : typeof instance === "symbol"
1. Null (Null тип ) : typeof instance === "object". Специальный примитив, используемый не только для данных но и в качестве указателя на финальную точку в Цепочке Прототипов;
2. Object (Объект) : typeof instance === "object". Простая структура, используемая не только для хранения данных, но и для создания других структур, где любая структура создаётся с использованием ключевого слова new: new Object, new Array, new Map, new Set, new WeakMap, new WeakSet, new Date и множество других структур;
3. и Function : typeof instance === "function". Специальный случай, упрощающий определение типа для Функций, несмотря на то, что все функции конструктивно унаследованы от Object.

