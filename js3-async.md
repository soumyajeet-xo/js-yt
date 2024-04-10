note : Master Async JavaScript by Sheriyan School on YT
link - https://www.youtube.com/watch?v=6kE8lrqfwHo

---

### JavaScript Concepts

- **`setTimeout`**
- **`setInterval`**
- **Promises**
- **Fetch**
- **Axios**
- **XML**

---

### Callback Functions

Callback functions are functions passed as arguments inside another function, which most probably is an asynchronous function, with the intention to be executed later or after an event has occurred.

---

### Asynchronous Code

JavaScript is single-threaded. It operates on a main stack and a side stack. When the main stack is empty, the side stack is checked.

Example:
```javascript
setTimeout(() => {
  console.log('Done');
}, 3000);
```

---

### Promises

Promises are used to avoid callback hell.

Example:
```javascript
let ans = new Promise((res, rej) => {
  if (true) {
    return res();
  } else {
    return rej();
  }
});

ans.then(() => {
  console.log("Resolved!");
}).catch(() => {
  console.log("Rejected!");
});
```

---

### Simple Callback

```javascript
setTimeout(() => {
  console.log('Done');
}, 1000);

function myCallback() {
  console.log('Done');
}

setTimeout(myCallback, 1000);
```

---

### Asynchronous Functions and `async/await`

```javascript
(async () => {
  console.log('Start');
  await new Promise(resolve => setTimeout(resolve, 1000));
  console.log('End');
})();
```

`async/await` can be used instead of `.then`. Use `async` functions when third-party is involved, where the completion time is not known.

---

### Concurrency and Parallelism

**Concurrency**: Managing multiple tasks in a single-threaded environment like JavaScript.

**Parallelism**: Ability to execute multiple operations simultaneously, focusing on processor cores and threads.

---

### Throttling

Throttling limits the rate at which a function can be executed. It ensures that the function is not called more frequently than a specified threshold.

---
