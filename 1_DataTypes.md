# DataTypes -

Type : what kind of data a variable can hold

```js
let a = 12;
let b = a;
b += 2;
console.log(a + " " + b); // 12 14
```
But in arrays, changes made in `b` affected `a`
```js
let a = [1, 2, 3, 4, 5];
let b = a;
b.pop();
console.log(a + " " + b); //1234 1234
```
These are references : [ ] , { } , ( )


## <center> Primitives
The most basic types in TypeScript are called primitives.
```ts
let isActive = true;

let decimal = 6;
let hex = 0xf00d;
let binary = 0b1010;
let octal = 0o744;      
let float = 3.14;      

let color = "blue";
let fullName = 'John Doe';
```


## <center> References [] {} ()

#### 1. ARRAYS :-
```JS
let a = [1,2,3,4,5, "AYUSH"];

let numbers: number[] = [1, 2, 3];

let names: Array<string> = ["A", "B"];
```

#### 2. TUPLES :-
```js
let tup:[string, number] = ["Ayush", 69]
```

#### 3. ENUM :-
```ts
enum UserRoles {
    ADMIN = "admin",
    GUEST = "guest",
    SUPER_ADMIN = "super_admin"
}
```
![alt text](image.png)  
we dont have to remember any property


---
#### 4. ANY :-  
Turns off TypeScript safety
```ts
let value: any = 10;
value = "hello"; // allowed (no safety)
```
---
#### 5. UNKNOWN :-  
Forces you to check type before using it
```ts
let value: unknown = 10;

if (typeof value === "string") {
  console.log(value.toUpperCase());
}
```

---
FUNCTIONS :-

```ts
function add(a: number, b: number): number {
  return a + b;
}
```