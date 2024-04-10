This is the note that i made while watching : JavaScript Advance Crash Course
link - https://youtu.be/EgDmCbhmstU?si=vrIsQsouYZtHoM_Q
---

## Differences between ES5 and ES6

### `var` vs. `let`
- **`var`**: Function-scoped.
- **`let`**: Block-scoped.

### Browser Features in `window` Object
- Features which are part of the browser but not part of core JavaScript can be found in an object called `window`.

### Execution Context
- The context where function code is executed.
- It contains three things: variable environment, function, and lexical environment.
- Lexical environment is like a book defining scope.

### Copying Reference Values
- To copy a reference value:
  ```javascript
  let a = [1, 2, 3, 4];
  let b = [...a];
  ```

### Callbacks
- Functions are first-class citizens in JavaScript.
- Callbacks are functions passed as arguments to other functions and can be executed asynchronously or at a later time.

### `delete` Operator
- Example: `delete a.age`

---
ofcourse, there are many more but this is what i wanted to note down.
