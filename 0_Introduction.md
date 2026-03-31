# Intro

Js had no type safety, a loosely typed language.

```js
var a = 69
a = "Ayush"
```

TypeScript is JavaScript with added syntax for types.  
It uses compile time type checking.

---

TypeScript has an official compiler  

    npm install -g typescript

    tsc fileName.ts  
    //To compile, we can write solely tsc too

    tsc --watch
    //no need to compile everytime

---
You will need ts.config file too


    tsc --init
    //If didn't work

    npx tsc --init


# TYPES -

The most basic types in TypeScript are called primitives.

```ts
let isActive: boolean = true;

let decimal: number = 6;
let hex: number = 0xf00d;       // Hexadecimal
let binary: number = 0b1010;     // Binary
let octal: number = 0o744;      // Octal
let float: number = 3.14;      // Floating point

let color: string = "blue";
let fullName: string = 'John Doe';
```