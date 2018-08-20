---
title: JavaScript Errors
tags: JavaScript
---

# Top 10 JavaScript Errors

## Uncaught TypeError: Cannot read property

Error In Chrome

**Mostly Cause By** Improper (不合时宜的) initialization of state while rendering the UI components;   
**Deal With** Initialize state with reasonable default values in the constructor.

## TypeError: ‘undefined’ is not an object

Same as First one，Error In Safari

## TypeError: null is not an object

Error In Safari

This is not same as last two errors，see：

1. Undefined is usually a variable that has not been assigned
2. Null means the value is blank

**May Cause By** Try using a DOM element in JavaScript before the element is loaded;   
**Deal With** Make sure executes and deals with DOM elements after the DOM elements have been created.

## (Unknown): Script error

Occurs when an uncaught JavaScript error crosses domain boundaries in violation of the cross-origin policy.

To Get Useful Information: 

1. Send the Access-Control-Allow-Origin header, Set * or your domain
2. Set crossorigin=”anonymous” on the script tag

## TypeError: Object doesn’t support property

Error In IE

**May Cause By** IE’s inability to bind methods within the current namespace to the this keyword;   
**Deal With** Using JS namespacing is to always prefix with the actual namespace.

Example:
````
this.isAwesone() => Rollbar.isAwesone()
````

## TypeError: ‘undefined’ is not a function

Error In Chrome

**May Cause By** Self-referencing scopes within callbacks and closures confusion;   
**Deal With** 

1. Save your reference to this in a variable that can then be inherited by the closure
2. Use the bind() method to pass the proper reference

## Uncaught RangeError: Maximum call stack

Error In Chrome

**Cause By**

1. Call a recursive (递归) function that does not terminate
2. Pass a value to a function that is out of range

## TypeError: Cannot read property ‘length’

Error In Chrome

**Cause By** Reading length property for an undefined variable:

1. Array is not initialized
2. Variable name is hidden in another context

## Uncaught TypeError: Cannot set property

Error In Chrome

**Cause By** Try to access an undefined variable

## ReferenceError: event is not defined

Error In Chrome

**Cause By** Try to access a variable that is undefined or is outside the current scope.

## Summary

Using TypeScript Make You More Safety!