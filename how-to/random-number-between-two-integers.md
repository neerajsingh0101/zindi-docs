
## How to get random number between two integers

```javascript
const max = 1000;
const min = 10;
const randomNumber = Math.random() * (max - min + 1) + min;
return Math.floor(randomNumber);
```
