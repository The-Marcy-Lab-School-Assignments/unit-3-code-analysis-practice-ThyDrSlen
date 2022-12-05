# unit-3-code-analysis-practice

Using markdown, identify what the following code block does and explain how the `forEach` function works.

```js
function forEach(arr, action) {
  for (let i = 0; i < arr.length; i++) {
    action(arr[i]);
  }
}

forEach(['a', 'b', 'c'], console.log);
```

**Guiding Questions:**
* What does the code do (what does it print? are any variable reassigned? etc...)
The function ForEach 
* What are the expected data types for each of the parameters?
* When the function is invoked, what value are provided as arguments?
* How does `forEach` use the provided arguments?

**Key Terms to use**: parameters, arguments, invoke/invocation, iterate, "element of the array", increment,  

<hr>

The parameters for the function `forEach` are `arr` and `action`. The arguments that are passed through are the `array = [‘a’, ‘b’, ‘c’]` and `console.log`. When the function gets invoked, the arguments are passed through and then the `for loop` gets iterate over each element, it console logs each element over each element and increments to the next element.
