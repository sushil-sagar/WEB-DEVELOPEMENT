ASYNC/AWAIT

---

1. **What is async/await in JavaScript?**
   - Async/await is a feature in JavaScript that allows you to write asynchronous code that looks and behaves like synchronous code. It is built on top of promises and provides a more concise and readable way to work with asynchronous operations.

2. **How do you define an async function?**
   - An async function is defined using the `async` keyword before the function declaration. For example:
     ```javascript
     async function myAsyncFunction() {
         // Async function body
     }
     ```

3. **How do you use await inside an async function?**
   - You use the `await` keyword before an asynchronous function call inside an async function. This keyword pauses the execution of the async function until the awaited promise is resolved or rejected. For example:
     ```javascript
     async function myAsyncFunction() {
         const result = await someAsyncOperation();
         // Continue execution after the promise is resolved
     }
     ```

4. **Explain the difference between async/await and promises.**
   - Async/await is a syntactic sugar built on top of promises. While promises are used to handle asynchronous operations and provide a way to chain them, async/await provides a more synchronous way of writing asynchronous code, making it easier to read and maintain.

5. **How do you handle errors in async/await functions?**
   - You can handle errors in async/await functions using try/catch blocks. If an awaited promise is rejected, the catch block will be executed, allowing you to handle the error. For example:
     ```javascript
     async function myAsyncFunction() {
         try {
             const result = await someAsyncOperation();
             // Continue execution after the promise is resolved
         } catch (error) {
             // Handle error
         }
     }
     ```

6. **Can you use async/await with regular synchronous functions?**
   - Yes, you can use async/await with regular synchronous functions. However, the synchronous functions will still be executed synchronously, and any asynchronous behavior will be limited to the async/await functions.

7. **How do you handle multiple async operations in parallel with async/await?**
   - You can use `Promise.all` with async/await to handle multiple async operations in parallel. `Promise.all` takes an array of promises and returns a single promise that resolves when all of the input promises have resolved or rejects as soon as one of the promises in the iterable rejects.

8. **What happens if an async function throws an error?**
   - If an async function throws an error, the promise returned by the function will be rejected with that error. You can use try/catch blocks or the catch method to handle the error.

9. **How do you chain async/await functions together?**
   - You can chain async/await functions together by using the `await` keyword to wait for the resolution of a promise returned by another async function. For example:
     ```javascript
     async function firstAsyncFunction() {
         const result = await secondAsyncFunction();
         // Continue execution after the promise is resolved
     }
     ```

10. **What is the benefit of using async/await over promises?**
    - Async/await provides a more readable and maintainable way to write asynchronous code compared to promises. It eliminates the need for explicit promise chaining and error handling, making the code easier to understand and debug.

---

Feel free to adjust the formatting or wording to better suit your README.md file!
