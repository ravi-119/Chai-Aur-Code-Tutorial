# Chai-Aur-Code-Tutorial

## JavaScript Basics

### Variables

In JavaScript, variables are used to store data values. You can declare variables using `const`, `let`, or `var`.

- `const`: Used for constants, whose values cannot be reassigned after initialization.
- `let`: Used for variables whose values may change during the execution of the program.
- `var`: Older way of declaring variables, with some scoping issues (avoid using it).

Example:

```javascript
const accountId = "4003001700024193";
let accountEmail = "ravikuamryadav70847@gmail.com";
var accountPassword = "12345678";
```

### Data Types

JavaScript has several built-in data types:

- **Number**: Represents numeric values (e.g., `18`, `3.14`).
- **BigInt**: Represents large integer values that cannot be represented by the Number type.
- **String**: Represents textual data (e.g., `"Ravi"`).
- **Boolean**: Represents `true` or `false` values.
- **Null**: Represents a deliberate non-value (e.g., `let state = null;`).
- **Undefined**: Represents a variable that has been declared but has not been assigned a value.
- **Symbol**: Represents unique identifiers.
- **Object**: Represents a collection of properties (e.g., objects, arrays).

Example:

```javascript
let name = "Ravi"; // string
let age = 18; // number
let isLoggedIn = false; // boolean
let state = null; // null
let undef; // undefined
```

### Conversion Operations

JavaScript allows you to convert values from one data type to another.

- `Number()`: Converts a value to a number.
  - `"33"` => `33`
  - `"33abc"` => `NaN`
  - `true` => `1`; `false` => `0`
- `Boolean()`: Converts a value to a boolean.
  - `1` => `true`; `0` => `false`
  - `""` => `false`
  - `"hitesh"` => `true`
- `String()`: Converts a value to a string.

Example:

```javascript
let score = "33";
let valueInNumber = Number(score);
console.log(valueInNumber); // 33

let isLoggedIn = 1;
let booleanIsLoggedIn = Boolean(isLoggedIn);
console.log(booleanIsLoggedIn); // true

let someNumber = 33;
let stringNumber = String(someNumber);
console.log(stringNumber); // "33"

