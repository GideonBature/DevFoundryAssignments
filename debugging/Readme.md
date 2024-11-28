# Example of Each Type of Bug

### Syntax Error
```javascript
function test() {
    return "Hello, World!";
```
This code has a syntax error because it is missing a closing bracket at the end of the function definition.

---

### Runtime Error
```javascript
const arr = [1, 2, 3];
arr[4] = 5;
```
This code has a runtime error because it is trying to access an index in the array that does not exist.

---

### Logic Error
```javascript
function calculateDiscount(price) {
    return price - 10 / 100;
}
calculateDiscount(150);
```
This code has a logic error because it is calculating the discount incorrectly. For a 10% discount, The correct calculation would be `price - (price * 10 / 100)` instead of just `price - 10 / 100`.

---

### Semantic Error
```javascript
function isOdd(number) {
    return number % 2 === 0;
}
isOdd(20);
```
This code has a semantic error because it is incorrectly defining what it means for a number to be odd. Hence, it will return `true` for even numbers instead of `false`.