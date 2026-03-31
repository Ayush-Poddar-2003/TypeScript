# Introduction to Ts

Js had no type safety, a loosely typed language.

```js
var a = 69
a = "Ayush"
```

TypeScript is JavaScript with added syntax for types.  

---
Browser only runs Js  
Js --> Compiler --> Ts

---

It uses compile time type checking.
TypeScript has an official compiler  

    npm install -g typescript

    tsc fileName.ts  
    //To compile, it will convert into .js


---
You will need `ts.config` file too  
Consists rules like, if variable left unused etc.

    tsc --init
    //If didn't work

    npx tsc --init

---
To avoid compiling everytime after making changes  
    
    tsc --watch

