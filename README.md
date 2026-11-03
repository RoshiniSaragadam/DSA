# Data Structures & Algorithms

## Arrays:
Examples of an arrays 

--removing even Integers from an array

```javascript
//remove even nos
const array = [3, 2, 4, 7, 5, 10, 6, 5];

function usingForLoop() {
    const oddArray = [];
    for (let index = 0; index < array.length; index++) {
        if (array[index] % 2 !== 0) {
            oddArray.push(array[index]);
        }
    }
    console.log(oddArray)
}

function usingForEach(){
    const oddArray = [];
    array.forEach(each => {
         if (each % 2 !== 0) {
            oddArray.push(each);
        }
    })
    console.log(oddArray)
}

usingForLoop();
usingForEach();
```
