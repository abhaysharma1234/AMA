# AMA Questions

## 1. How to handle Promises?
Use .then(), .catch(), and .finally()

Example:
promise.then(res => console.log(res))
       .catch(err => console.error(err))
       .finally(() => console.log("Done"));

## 2. Functions of Promise
- resolve()
- reject()

## 3. What is a Higher Order Function?
A function that takes or returns another function.

## 4. What is Call Stack?
A LIFO structure that tracks function execution.

## 5. Async and Await in JS
Simplifies working with promises.

Example:
async function getData() {
  const res = await fetch(url);
}

## 6. What is Object?
A collection of key-value pairs.

Example:
const obj = { name: "Abhay", age: 21 };

## 7. How to access HTML in JS?
Example:
document.getElementById("id");
document.querySelector(".class");

## 8. Promise States
- Pending
- Fulfilled
- Rejected

## 9. What is flat() method?
Flattens nested arrays.

Example:
[1, [2, 3]].flat(); // [1, 2, 3]

## 10. Output of null + 1
null + 1 // 1

## 11. Object Methods
- Object.keys()
- Object.values()
- Object.entries()

## 12. Other Console Methods
- console.log()
- console.error()
- console.warn()
- console.table()

## 13. Which promise returns first resolved/rejected?
Promise.race()

## 14. Types of Operators
- Arithmetic
- Comparison
- Logical
- Assignment
- Bitwise

## 15. Freeze function of Object
Prevents modification.

Example:
Object.freeze(obj);
