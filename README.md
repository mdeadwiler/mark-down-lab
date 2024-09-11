
# Writing a Function in JavaScript

![ART](https://images.unsplash.com/photo-1722970651121-6a3ea5666ff7?w=800&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHx0b3BpYy1mZWVkfDl8Q0R3dXdYSkFiRXd8fGVufDB8fHx8fA%3D%3D)

In JavaScript, functions are blocks of reusable code. They allow you to bundle functionality, make it more readable, and avoid repetition. Here's a brief tutorial on writing an arrow function in JavaScript.

## Basic syntax

```javascript
const functionName = (params) => {
  // code to be executed
}
```

1. **const**: const should be used whenever a function expression is assigned to a variable.
2. **The function name**: The name you choose for the function.
3. **Parameters**: Optional comma separated parameters. This is the data passed into the function. If there are no parameters, the () is still required.
4. **The arrow syntax**: Indicates that this will be a function.
5. **The body**: The statements that make up the function itself. Surrounded by curly braces.

 ***Example***:

```javascript
const greet = (name) => {
  console.log("Hello, " + name + "!");
}
```

>**Tip**: Functions often perform actions, so naming with a verb can make it clear what the function does. Examples include fetchData( ), calculateArea( ), or printReport( ).

### Calling a function

To execute the function, you call or invoke it by using its name followed by parentheses.

 ***Example***:

*greet('Alice'); // Outputs: Hello, Alice!*

Return values

Functions can process data input and output a value using the return keyword.

 ***Example***:

```javascript
const addNums = (numA, numB) => {
  return numA + numB*
}
```

const total = addNums(2, 4);

console.log(total) // Expected value: 6

For more information on functions and how they are used in JS, check out the [MDN Docs](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Functions).

# NFL Memory Game

![NFL](data:image/jpeg;base64,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)

## ***Rules and how to play the game***:
+ This NFL-themed memory game challenges players to match current NFL players hidden behind a grid of squares. Players will select squares, trying to find matching pairs within 8 attempts. Each round consists of 12 squares, and you'll have 16 seconds to make your selections. With each new round, the time to complete your matches decreases, raising the stakes. To win, you must successfully match three pairs in a row.
  
### ***Cool part of the game***:
+ Each NFL player will have a voice over if the matches are correct!

#### ***Some Syntax***:
```javascript
function shuffle(array) {
        for (let i = array.length - 1; i > 0; i--) {
            const j = Math.floor(Math.random() * (i + 1));
            [array[i], array[j]] = [array[j], array[i]];
        }
        return array;
    }

```
>#### **Tip**: 
+ Look on the NFL site to reference current and relevant players [NFL](https://www.nfl.com/)

***Go Raiders!***

![Raiders](data:image/jpeg;base64,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)