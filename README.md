# javascript-test-0003-final-17958-chetan
Final Project Assignment - This repository contains the complete final project code and documentation.

## Assignment - 3 Solution 

```
let n = 6;

for (let i = 1; i <= n; i++) {

    let num = i % 2;

    for (let j = 1; j <= i; j++) {
        process.stdout.write(num + " ");
        num = num === 1 ? 0 : 1;
    }

    console.log();
}
```
