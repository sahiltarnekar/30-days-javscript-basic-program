# 🔄 Day 2: Swap Two Numbers Using a Temporary Variable (JavaScript)

## ✅ Program Goal
Swap the values of two variables using a **temporary third variable** in JavaScript.

---

## 💻 Code:
```js
let a = 10;
let b = 20;

console.log("Before Swapping: a =", a, ", b =", b);

let temp = a;  // Store value of a in temp
a = b;         // Assign value of b to a
b = temp;      // Assign value of temp (original a) to b

console.log("After Swapping: a =", a, ", b =", b);
