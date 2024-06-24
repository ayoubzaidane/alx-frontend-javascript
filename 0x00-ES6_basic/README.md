# Learning ES6 (ECMAScript 2015)

Welcome to my journey of learning ES6 (ECMAScript 2015)! This repository contains notes, examples, and explanations of the new features introduced in ES6.

## Table of Contents

- [Introduction](#introduction)
- [What is ES6?](#what-is-es6)
- [New Features Introduced in ES6](#new-features-introduced-in-es6)
  - [Constants and Variables](#constants-and-variables)
  - [Block-Scoped Variables](#block-scoped-variables)
  - [Arrow Functions](#arrow-functions)
  - [Rest and Spread Function Parameters](#rest-and-spread-function-parameters)
  - [String Templating](#string-templating)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This repository is dedicated to learning ES6, also known as ECMAScript 2015. ES6 introduced several new features and syntax improvements to JavaScript, making it easier to write and maintain code.

## What is ES6?

ES6, or ECMAScript 2015, is the sixth edition of the ECMAScript standard. It introduced significant improvements and new features to the JavaScript language, aimed at making it more powerful and easier to work with.

## New Features Introduced in ES6

### Constants and Variables

In ES6, you can define constants using the `const` keyword and variables using the `let` keyword. 

- `const`: Used to declare a constant value that cannot be reassigned.
- `let`: Used to declare a variable with block scope.

```javascript
const PI = 3.14159;
let age = 25;

age = 26; // This is allowed
PI = 3.14; // This will throw an error

