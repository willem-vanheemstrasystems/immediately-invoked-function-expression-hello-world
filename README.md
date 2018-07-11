immediately-invoked-function-expression-hello-world
# Immediately Invoked Function Expression (IIFE) - Hello World

Based on "10 JavaScript concepts every Node.js programmer must master" at https://www.infoworld.com/article/3196070/node-js/10-javascript-concepts-nodejs-programmers-must-master.html#tk.ifw-infsb

An immediately invoked function expression (IIFE) is a function that's executed as soon as it's created. It has no connection with any events or asynchronous execution. You can define an IIFE as shown below:

```javascript
(function() {
     // all your code here
     // ...
})();
```

The first pair of parentheses function(){...} converts the code inside the parentheses into an expression.The second pair of parentheses calls the function resulting from the expression. An IIFE can also be described as a self-invoking anonymous function. Its most common usage is to limit the scope of a variable made via var or to encapsulate context to avoid name collisions.
