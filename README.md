# EcmaScript 7 Basic Guide
A common project made by Better Code developers.

## ES7: Async and Await

A great example of async/await:

```js
async function asyncFun () {
  var value = await Promise
    .resolve(1)
    .then(x => x * 3)
    .then(x => x + 5)
    .then(x => x / 2);
  return value;
}
asyncFun().then(x => console.log(`x: ${x}`));
```

### Resources

[Understanding JavaScript’s async await](https://ponyfoo.com/articles/understanding-javascript-async-await)
