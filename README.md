# Web 3 Javascript Refresh

```
const a = 99

module.exports = a;
```

```
const a = true;
const b = false;

module.exports = { a, b }
```

```
function addTwo(input) {
    return input + 2;
}

module.exports = addTwo;
```

* boolean
```
true
false
```

* function
```
function getNumber() {
    return 4;
}

const num = getNumber();
```

```
function isEqual(a, b) {
    if(a === b){
        return true;
    }
}

module.exports = isEqual;
```

* Math object 
```
const myRandomNumber = Math.random(); // return some number between 0 and 1 (not including 1).
const two = Math.floor(2.2598223);
```

* Loop
```
let sum = 0;
for(let i = 1; i <= 4; i++) { 
    sum = sum + i; 
}
```

```
function summation(n) {
    let sum = 0;

    for (let i = 1; i <= n; i++) {
        sum += i;
    }

    return sum;
}

module.exports = summation;
```

> A factorial is the product of all positive integers greater than 0 up to and including the factorial number n.
```
5! = 5 * 4 * 3 * 2 * 1 = 120

3! = 3 * 2 * 1 = 6

2! = 2 * 1 = 2
```
```
function factorial(n) {
    let factorial_n = 1;
    for(let i = 1; i <= n; i++){
        factorial_n *= i 
    }
    return factorial_n;
}

module.exports = factorial;
```

```
function topDouble(value, top) {
    let totalValue = value;
    while(totalValue < top){
        totalValue *= 2
    }
    return totalValue / 2;
}

console.log(topDouble(1, 5))
console.log(topDouble(2, 100))
console.log(topDouble(5, 100))
```