# EPAM_JS_Automation_3

let str = 'JS Automation';
let boolF = false;
let boolT = true;
let num = 3;
let numStr = '4';

// Выполнить сложение различных типов(string+boolean, string+number, number+boolean)
console.log(`Addition of string and boolean ${str} + ${boolT} = ${str + boolT}`); // 'JS Automationtrue'

console.log(`Addition of string and nubmer "${str}" + ${num} = ${str + num}`); // 'JS Automation3'

console.log(`Addition of number and boolean ${num} + ${boolF} +${boolT} = ${num + boolF + boolT}`); // 3+ 0 + 1 = 4

console.log();

// Выполнить умножение различных типов(string * boolean, string * number, number * boolean)
console.log(`Multiplication of string and boolean "${str}" * ${boolT} = ${str * boolT}`); // NaN

console.log(`Multiplication of string and number "${str}" * ${num} = ${str * num}`); // NaN

console.log(`Multiplication of numeric string and number "${numStr}" * ${num} = ${numStr * num}`); // 12

console.log(`Multiplication of number and boolean ${num} * ${boolT} = ${num * boolT}`); // 3

console.log(`Multiplication of number and boolean ${num} * ${boolF} = ${num * boolF}`); // 0

console.log(`Multiplication of numeric string and boolean "${numStr}" * ${boolT} = ${numStr * boolT}`); // 4

console.log();

// Выполнить деление различных типов(string/boolean, string/number, number/Boolean)
console.log(`Division of string by boolean ${str} / ${boolT} = ${str / boolT}`); // NaN

console.log(`Division of string by number ${str} / ${num} = ${str / num}`); // NaN

console.log(`Division of numeric string by number "${numStr}" / ${num} = ${numStr / num}`); // NaN

console.log(`Division of number by boolean ${num} / ${boolT} = ${num / boolT}`); // 3

console.log(`Division of number by boolean ${num} / ${boolF} = ${num / boolF}`); // Infinity

console.log();

// Выполнить явное преобразование(number, string, boolean)
console.log(`Type change number ${num} to String "${String(num)}"`);

console.log(`Type change numeric string ${numStr} to number. +"${numStr}" -> ${+numStr}`);

console.log(`Type change boolean ${boolT} to number. +${boolT} -> ${+boolT}, ${boolT} * 1 -> ${boolT * 1}`);
