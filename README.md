#### Utilsverse-demo
Utilsverse Documentation 



## PascalCase
```js
// import module
import {PascalCase} from 'utilsverse/PascalCase';

// example string
let str = "abcd efgh";

// printing str in PascalCase
console.log(PascalCase(str));

// Output -> AbcdEfgh
```

## camelCase
```js
// import module
import camelCase from 'utilsverse/camelCase';

// example string
let str = "abcd efgh";

// printing str in camelCase
console.log(camelCase(str));

// Output -> abcdEfgh
```

## snake_case
```js
// import module
import snake_case from 'utilsverse/snake_case';

// example string
let str = "aecd efgh";

// printing str in snake_case
console.log(snake_case(str));

// Output -> aecd_efgh
```

## firstCap
```js
// import module
import firstCap from 'utilsverse/firstCap'

// example string
let str = "aeGd efgh ijkL";

// printing str
console.log(firstCap(str));

// Output -> Aegd Efgh Ijkl
```

## onlyFirstCap
```js
// import module
import onlyFirstCap from 'utilsverse/onlyFirstCap'

// example string
let str = "aeGd efgh ijkL";

// printing str
console.log(onlyFirstCap(str));

// Output -> Aegd efgh ijkl
```

## removeHTMLTags
```js
// import module
import removeHTMLTags from 'utilsverse/removeHTMLTags'

// example tag
let tags = "<h1> Hello World! </h1>";

// printing tags
console.log(removeHTMLTags(tags));

// Output -> Hello World! 
```

## debounce - works on DOM.
```js
// import module
import debounce from 'utilsverse/debounce';

// debounce function
debounce(()=>{
  // callback
},time);

Ex - 
debounce(()=>{
  // callback
},1000);
```

## throttle - works on DOM.
```js
// import module
import throttle from 'utilsverse/throttle';

// throttle function
throttle(()=>{
  // callback
},1000);

Ex -
throttle(()=>{
 // callback
},1000);
```

## delay
```js
// import module
import delay from 'utilsverse/delay';

// example function
function example() {
    console.log("hello world!");
}

// call delay function
delay(example, 1000)

// Output -> hello world! (will be printed after 1 sec)
```

## date_dmy
```js
// import module
import dmy from 'utilsverse/date_dmy';

// convert today's date to dd-mm-yyyy format
console.log(dmy())

// Documented on - 17th July, 2023
// Output -> 17-07-2023
```

## date_mdy
```js
// import module
import mdy from 'utilsverse/date_mdy';

// convert today's date to dd-mm-yyyy format
console.log(mdy())

// Documented on - 17th July, 2023
// Output -> 07-17-2023
```

## date_ymd
```js
// import module
import ymd from 'utilsverse/date_ymd';

// convert today's date to dd-mm-yyyy format
console.log(ymd())

// Documented on - 17th July, 2023
// Output -> 2022-07-17
```

## isLeap
```js
// import module
import isLeap from 'utilsverse/isLeap';

// calling isLeap Fn
console.log(isLeap(2020));

// Output -> true
```

## formate_date_util
```js
// import module
import util from 'utilsverse/format_date_util';

// return day, date and year
console.log(util(new Date()))

// Documented on - 17th July, 2023
// Output -> { day: '17', month: '07', year: 2023 }
```

## randomNumberInRange
```js
// import module
import random from 'utilsverse/randomNumberInRange';

// generate random number in range 1 - 100
console.log(random(1,100));

// Output -> 28 (may vary)
```

## triggerFnPerSec
```js
// import module
import triggerFnPerSec from 'utilsverse/triggerFnPerSecond';

// example function
function example() {
    console.log("hello world!");
}

// call trigger function
triggerFnPerSec(example)

// Output -> hello world
// will be keep printed after 1 sec
```

## triggerFnPerInterval
```js
// import module
import triggerFnPerInterval from 'utilsverse/triggerFnPerInterval';

// example function
function example() {
    console.log("hello world!");
}

// call trigger function
triggerFnPerInterval(example, 1500)

// Output -> hello world
// will be keep printed after 1.5 sec
```
