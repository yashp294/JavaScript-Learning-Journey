# Data Types & Primitive Types (Topic 02)

> **Category**: Fundamentals  
> **Study Duration**: 8 minutes  
> **Status**: Mastered & Solved ✅  
> **Platform**: [Stacckly JavaScript Mastery](https://stacckly-js-mastery.web.app)

---

## 📖 Topic Overview
Primitive data types in JS are the fundamental building blocks: Number, String, Boolean, Null, and Undefined.

---

## 🧠 Core Concepts & Mechanics
### 1. Concept Point
1. Number: Represents numeric values (both integers and floats) and supports arithmetic operations.

### 2. Concept Point
2. String: Represents textual data enclosed in single (''), double (""), or backtick (``) quotes.

### 3. Concept Point
3. Boolean: Represents logical truth values: true or false.

### 4. Concept Point
4. Null: Represents the intentional absence of any object value.

### 5. Concept Point
5. Undefined: Represents an uninitialized variable or missing property value.

### 6. Concept Point
Important Quirk: `typeof null` returns `"object"`, which is a historical JavaScript quirk.

---

## 💡 Key Takeaways & Best Practices
- JavaScript has dynamic typing: variables can hold values of any type at runtime.
- Use strict equality (===) to avoid unintentional type coercion.
- Remember typeof null === "object", while typeof undefined === "undefined".

---

## 🎯 Tailored DSA Challenge: Inspect Primitive Types with typeof
- **Difficulty**: `Easy`
- **Execution Mode**: `Script / Console Output`

### Problem Statement
Declare a variable `let score = 95;` and log its type using `console.log(typeof score)`. Next, declare `let language = "JavaScript";` and log its type using `console.log(typeof language)`.

### Examples
#### Example 1
- **Input**: `let score = 95; console.log(typeof score);`
- **Output**: `"number"`


#### Example 2
- **Input**: `let language = "JavaScript"; console.log(typeof language);`
- **Output**: `"string"`



---

## 💻 Verified Solution Code (`solution.js`)
```javascript
let score = 95;
// Log typeof score
console.log(typeof score);

let language = "JavaScript";
// Log typeof language
console.log(typeof language);
```

---
*Auto-generated & committed by [Stacckly](https://stacckly-js-mastery.web.app) • Master JavaScript with Consistency.*
