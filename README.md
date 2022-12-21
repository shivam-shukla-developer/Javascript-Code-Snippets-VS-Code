# JavaScript Code Snippets

---

This extension contains javascript code snippets for [Visual Studio Code](https://code.visualstudio.com/) editor.

[Author - Shivam Shukla ](https://shivamshukla.online/) | 
[Marketplace](https://marketplace.visualstudio.com/items?itemName=ShivamShukla.js-code-snippets)


## Snippets

List of all available snippets is given below.

### Function

| Trigger | Content                                                                            |
| ------- | ---------------------------------------------------------------------------------- |
| `nfn`   | create a funtion with function keyword `function functionName () {}`               |
| `fn`    | create a anonymous function `function () {}`                                       |
| `afn`   | create a arrow function `const functionName= () => {}`                             |
| `apply` | create an apply funtion `functionName.apply(this,arguments)`                       |
| `call`  | create a call function `functionName.call(this,arguments)`                         |
| `iife`  | create iife function `(function() {} ();)`                                         |
| `iifer` | create iife function with return value `const result=(function(){ return ; } ();)` |

### Promise

| Trigger | Content                                                                            |
| ------- | ---------------------------------------------------------------------------------- |
| `np`    | create a promise with then and catch methods `new Promise((res, rej) => {})`       |
| `npres` | create a promise and resolve it `Promise.resolve()`                                |
| `nprej` | create a promise and reject it `Promise.reject()`                                  |
| `npf`   | create a promise with try, catch and finally block                                 |
| `npall` | Promise.all method `Promise.all()`                                                 |
| `npany` | Promise.any method `Promise.any()`                                                 |
| `nprace`| Promise.race method `Promise.race()`                                               |
| `npallsettled` | Promise.all method `Promise.allsettled()`                                   |

### Array Methods

| Trigger  | Content                                                                                |
| -------- | ------------------------------------------------------------------------------         |
| `arrmth` | create Array method for - forEach, map, filter, find, every, some.                     |
| `arrconcat` | Array concat method `array1.concat(array2);`                                        |
| `arrcopyWithin`| Array copyWithin method `array1.copyWithin(array2);`                             |
| `arrentries`   | Array copyWithin method `array.entries();`                                       |
| `arrfilter`    | Array filter method `array.filter((item, index, array) => {});`                  |
| `arrfindIndex` | Array findIndex method `array.findIndex((item, index, array) => {});`            |
| `arrflat`      | Array float method `array.flat();`                                               |
| `arrflatmap`   | Array float method `array.flatMap((item, index, array) => {});`                  |
| `arrforEach`   | Array forEach method `array.forEach((item, index, array) => {});`                |
| `arrfrom`      | Array from method `Array.from(array, item => {});`                               |
| `arrisArray`   | Array isArray method `Array.isArray(array);`                                     |
| `arrincludes`  | Array includes method `array.includes(value);`                                   |
| `arrindexOf`   | Array indexOf method `array.indexOf(value);`                                     |
| `arrjoin`      | Array join method `array.join(string);`                                          |
| `arrkeys`      | Array keys method `array.keys();`                                                |
| `arrmap`       | Array map method `array.map(function (element, index, array) { }, thisArg);`     |
| `arrof`        | Array of method `Array.of(element0, element1);`                                  |
| `arrpop`       | Array pop method `array.pop();;`                                                 |
| `arrpush`      | Array push method `array.push('');`                                              |
| `arrreduce`    | Array reduce method `array.reduce((accumulator, currentValue, currentIndex, array) => { });`                                                                                           |
| `arrreduceRight`    | Array reduceRight method `array.reduceRight((accumulator, currentValue, currentIndex, array) => { });`                                                                      |
| `arrreverse`   | Array reverse method `array.reverse('');`                                        |
| `arrshift`     | Array shift method `array.shift('');`                                            |
| `arrslice`     | Array slice method `array.slice(begin, end);`                                    |
| `arrsome`      | Array some method `array.some(function (element, index, array) { }, thisArg);`   |
| `arrsort`      | Array sort method `array.sort((a, b) => { } );`                                  |
| `arrsplice`    | Array splice method `array.splice(start, deleteCount, item1, item2, itemN);`     |
| `arrunshift`   | Array unshift method `array.unshift(element0, element1, /* … ,*/ elementN);`     |

### Object Methods

| Trigger  | Content                                                                                |
| -------- | ------------------------------------------------------------------------------         |
| `objkeys`          | Object keys method `Object.keys(myObj)`                                      |
| `objkeysforeach`   | Object keys metod with foreach method `Object.keys(myObj).forEach((key, index) => {})`                                                                                             |
| `objvalues`        | Object values method `Object.values(myObj)`                                  |
| `objvaluesforeach` | Object values metod with foreach method `Object.values(myObj).forEach((key, index) => {})`                                                                                                |
| `objentries`       | Object entries method `Object.entries(myObj)`                                |
| `objentriesforeach`| Object entries metod with foreach method `Object.entries(myObj).forEach((key, index) => {})`                                                                                                |
| `objassign`        | Object assign method `Object.assign(target, source)`                         |
| `objfreeze`        | Object freeze method `Object.freeze(obj)`                                    |
| `objis`            | Object is method `Object.is(value1, value2)`                                 |
| `objtoString`      | Object toString method `obj.toString()`                                      |
| `objprototype.toString` | Object prototype toString method `obj.prototype.toString=function(){};` |
| `objhasOwnProperty`| Object hasOwnProperty method `obj.hasOwnProperty(property);`                 |
| `objgetOwnPropertyNames`| Object getOwnPropertyNames method `Object.getOwnPropertyNames(obj);`    |
| `objgetOwnPropertyDescriptor`| Object getOwnPropertyDescriptor method `Object.getOwnPropertyDescriptor(obj, property);`                                                   | 


### Conditional Operator

| Trigger | Content                                    |
| ------- | ------------------------------------------ |
| `i`     | Basic if statment `if(conditon) {}`        |
| `ife`   | If-else statment `if(conditon) {} else {}` |
| `ei`    | Else if statment `else if(condition) {}`   |
| `swt`   | Switch Statment                            |

```
switch(expression){
    case condition: //...
                    break;
    case condition: //...
                    break;
    default: //....
}
```

### Loops

| Trigger | Content                                   |
| ------- | ----------------------------------------- |
| `fin`   | For in loop `for(const key in source) {}` |
| `fof`   | For of loop `for(cont key of source) {}`  |
| `wl`    | while loop `while(condition) {}`          |

### Fetch Request

`fetch`→ Fetch Request

```
fetch('url')
    .then(res => res.json())
    .then(data => console.log(data));
```

`fetchc`→ Fetch with catch

```
fetch('url')
    .then(response => {
        if (response.status === 200) {
            return response.json();
        } else {
            throw new Error('Something went wrong on api server!');
        }
    })
    .then(data => {
        console.debug(data);
    }).catch(error => {
        console.error(error);
    });
```

`asyncfetch`→ Async/Await Fetch Request

```
const request = async () => {
    const response = await fetch('url');
    const data = await response.json();
    console.log(data);
}
```

### Exception Handling

| Trigger | Content                                                  |
| ------- | -------------------------------------------------------- |
| `tc`    | Try and Catch `try {} catch(err) {}`                     |
| `tcf`   | Try, Catch and Finally `try {} catch(err) {} finally {}` |

### Axios

`ax`→ Axios Request for all get, post, put, delete

```
axios.(get,post,put,delete)('url')
    .then(res => console.log(res.data))
    .catch(err => console.log(err));
```

`asyncax`→ Axios Request for all get, post, put, delete

```
async function functionName() {
    try {
      const response = await axios.(get,post,put,delete)('url');
      const data = await response.json();
      return data;
    } catch (error) {
      console.log(error);
    }
}
```

### Timer

| Trigger | Content                                                                       |
| ------- | ----------------------------------------------------------------------------- |
| `st`    | Set Timeout `setTimeout(() => {}, delay)`                                     |
| `si`    | Set Interval `setInterval(() => {}, intervalInms)`                            |
| `sim`   | Set Immediate `setImmediate(() => {})`                                        |
| `stv`   | Set TimeOut with variable `const timer = setTimeout(() => {}, delay)`         |
| `ct`    | Clear Timeout `clearTimeout(variableName)`                                    |
| `siv`   | Set Interval with variable `cont timer = setInterval(() => {}, intervalInms)` |
| `ci`    | Clear Interval `clearInterval(variableName)`                                  |

### Destructure

| Trigger | Content                                                    |
| ------- | ---------------------------------------------------------- |
| `ad`    | Array Destructure `const [element1, element2] = array`     |
| `od`    | Object Destructure `const {property1, property2} = object` |

### ES6 Modules

| Trigger | Content                                                                   |
| ------- | ------------------------------------------------------------------------- |
| `ed`    | export default `export default member`                                    |
| `edf`   | export default named function `export default function functionName() {}` |
| `ec`    | export const `export const member = value`                                |
| `im`    | import `import * from 'module'`                                           |
| `ima`   | import as `import * as name from 'module'`                                |
| `imd`   | import with destructure `import { } from 'module'`                        |
| `rq`    | require `const module = require(module)`                                  |
| `me`    | module exports `module.exports = {}`                                      |

### Class

`cls`→ class

```
class name {
    constructor() {
    }
}
```

`clsx`→ class with extends

```
class name extends base {
    constructor() {
      super();
    }
}
```

### Console

| Trigger | Content                                                      |
| ------- | ------------------------------------------------------------ |
| `clog`  | console.log `console.log(obj);`                              |
| `cl`    | console log with key value pair `console.log('obj:',obj);`   |
| `cclr`  | console clear `console.clear();`                             |
| `cw`    | console warn `console.warn(obj);`                            |
| `ctb`   | console table `console.table(obj);`                          |
| `cass`  | console assert `console.assert(expression, obj);`            |
| `cc`    | console count `console.count(label);`                        |
| `ccr`   | console countrest `console.countReset(label);`               |
| `cdir`  | console dir `console.dir(obj, {colors: true, depth: null});` |
| `cerr`  | console error `console.error(obj);`                          |
| `cgrp`  | console group `console.group(label);`                        |
| `cend`  | console groupend `console.groupEnd();`                       |
| `cin`   | console info `console.info(obj)`                             |
| `ctym`  | console time `console.time(label);`                          |
| `cte`   | console timeend `console.timeEnd(label);`                    |
| `ctg`   | console timelog `console.timeLog(label);`                    |
| `ctr`   | console trace `console.trace(label);`                        |