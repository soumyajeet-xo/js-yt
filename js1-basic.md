This is the note that i made while watching : JavaScript Crash Course: Master the Basics by Shriyans Coding on Yt
link - https://youtu.be/htznIeWKgg8?si=IVfQLPGnTHSS5lUR
---

## Keywords and Concepts in JavaScript

### Comments
- `//` for single line comments.

### `var`, `let`, `const`
- `var`, `let`, and `const` are keywords used for variable declarations.
- Differences between `var` and `let`:
  - **Scope**: `var` is function-scoped or globally-scoped, while `let` is block-scoped.
  - **Hoisting**: Variables declared with `var` are hoisted (their declaration is moved to the top of their scope). Variables declared with `let` are also hoisted but not initialized.
  - **Redeclare and Reinitialize**: Variables declared with `var` can be redeclared and reinitialized. Variables with `let` can be reinitialized but not redeclared in the same scope.

### Hoisting
- Hoisting is a concept in JavaScript wherein variable and function declarations are moved to the top of their containing scope during the compilation phase.

### Undefined and Not Defined
- **undefined**: A variable that has been declared but not assigned a value.
- **not defined**: An error thrown when attempting to use a variable that has not been declared.

### Primitive/Predefined Datatype
- **Number**
  ```javascript
  let age = 25; // Integer
  let price = 99.99; // Floating-point number
  ```
- **String**
  ```javascript
  let name = 'Alice';
  let greeting = "Hello, " + name;
  ```
- **Boolean**
  ```javascript
  let isOpen = true;
  ```
- **undefined**
  ```javascript
  let result;
  console.log(result); // Outputs: undefined
  ```
- **null**
  ```javascript
  let data = null;
  ```
- **Symbol**
  ```javascript
  let symbol1 = Symbol('identifier');
  let symbol2 = Symbol('identifier');
  console.log(symbol1 === symbol2); // Outputs: false
  ```
- **BigInt**
  ```javascript
  let bigNumber = 1234567890123456789012345678901234567890n;
  ```

### Reference Types (Objects)/User-Defined
- **Object**
  ```javascript
  let person = {
    name: 'Alice',
    age: 25
  };
  ```
- **Array**
  ```javascript
  let colors = ['Red', 'Green', 'Blue'];
  ```
- **Function**
  ```javascript
  function greet(name) {
    return `Hello, ${name}!`;
  }
  ```

### Primitive vs. Reference Types
- **Primitive**: On copy, the actual value gets copied.
- **Reference**: On copy, a reference to the original gets copied.

### Deep Copy vs. Shallow Copy

### Conditionals
- `if`, `else if`, `else`
- **Truthy and Falsy**: All numbers except `0` and `-0` are truthy.

### Loops
- Used wherever there is repetition.
- **For loop**

### Array Operations
- `push`, `pop`, `shift`, `unshift`
  - **unshift**: Put at the start.
  - **shift**: Remove at the start.
  - `arr.splice(2,1)`: Removes 1 value at index 2.

### Object

---
