# random-number
### generate a random number using `javascript` within the range of given two numbers

### __Note:__
* We will define `max` and `min` numbers to generate a random number between those two. 
* The generated number can be *less than* the `max` number but *more than and not equal* to the `min` number.

```javascript
function generateNumber(max,min) { 
  return Math.floor(Math.random() * (max - min + 1)) + min;
}

console.log(generateNumber(max,min));
```
