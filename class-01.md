# Node Ecosystem, TDD, CI/CD

### Definitions:

1- **Array.map()**:The map() method creates a new array with the results of calling a function for every array element. The map() method calls the provided function once for each element in an array, in order.

2- **Array.reduce()**: The reduce() method reduces the array to a single value. The reduce() method executes a provided function for each value of the array (from left-to-right). The return value of the function is stored in an accumulator (result/total).

3- **SuperAgent**: is a light-weight, flexible and expressive Ajax library. ... The Github APIs support CORS and so you can make Ajax requests to them directly from here.
 
**superagent with then/catch**
```
superagent.post('/api/pet').then(console.log).catch(console.error);
 ```

**// **promise with async/await**
```
(async () => {
  try {
    const res = await superagent.post('/api/pet');
    console.log(res);
  } catch (err) {
    console.error(err);
  }
})();
```