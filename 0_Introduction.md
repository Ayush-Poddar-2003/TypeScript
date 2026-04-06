# <center>Introduction

Js had no type safety, a loosely typed language.

```js
let a:number = 69
a = "Ayush"
```

TypeScript is better version of js with added syntax for types.  

---

### Ts Compiler Installation -

    npm install -g typescript

To Compile :-

    tsc fileName.ts  // it will create a .js


### Project Setup -

You will need `ts.config` file, Settings file  
Consists rules like, if variable left unused, undefined   etc.

    tsc --init //to create ts.config

    npx tsc --init //if above didn't work

---
To avoid compiling everytime after making changes  
    
    tsc --watch 

