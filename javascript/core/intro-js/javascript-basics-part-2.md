---
author: alexjmackey

type: normal

category: must-know

aspects:
  - introduction


---
# JavaScript Basics - Part 2

---
## Content

Here's a couple more rules.

### Case Sensitivity

Everything in JavaScript is case sensitive.

```js
let password;
// Is not the same as
let pasSword;
// or
let PASSWORD;
```

### Keywords

Like most languages, there are a number of reserved words in JavaScript that you cannot use to name your functions and variables (e.g. `var`, `let`, `new`).

### Identifier naming rules

When naming any function, property or variable, the first character must be a letter, $ sign or underscore.

After the first character, you are free to use numbers, letters, dollar signs or underscores.

```javascript
let name = "Enki"; // valid
let $taxRate = 8.25; // valid
let _id = 23; // valid
let 2Company = "Enki"; // not valid
```

### Comments

Comments can be created in 2 ways in JavaScript.

As a single line comment:

```js
// I am a single line comment
```

You can also add single line comments to the same line as other code:

```javascript
let company="enki"; // define company
```

Or if you have more text you can use a block comment:
```javascript
/*
I am a block comment
*/
```

### Semicolon

Statements in JavaScript end in a `;`. Based on the ECMAScript[1] rules however, adding a `;` isn't actually required (although it is common practice):

```javascript
let firstName = "Enki";
//                    ^
```

Omitting a semicolon in certain situations can cause problems. JavaScript has a feature called Automatic Semicolon Insertion (ASI) which means that, if you omit a semicolon, JavaScript will automatically add it where it thinks it should go. 

This can sometimes lead to unexpected results[2]. Thus, it's usually recommended to insert the `;` yourself.

---
## Practice

What syntax is used in *JavaScript* for **single line** comments?

???

* //
* `/* */`
* `#`

---
## Revision

Is the following line of code **valid**?

```javascript
let 777jackpot = "jackpot";
// line is ???
```

* not valid
* valid

---
## Quiz
### which of the following is a valid comment?

```javascript
(1. // first comment
(2. <!-- second comment
(3. /* third comment */
```

 ???

* 1, 2 & 3
* 1
* 1 & 3
* 2
