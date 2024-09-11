
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
