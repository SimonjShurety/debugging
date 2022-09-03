# debugging

https://www.theodinproject.com/lessons/foundations-understanding-errors

https://developer.chrome.com/docs/devtools/javascript/

https://googlechrome.github.io/devtools-samples/debug-js/get-started

https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/What_went_wrong

https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors



## In the Console drawer, type parseInt(addend1) + parseInt(addend2). This statement works because you are paused on a line of code where addend1 and addend2 are in scope.

## Press Enter. DevTools evaluates the statement and prints out 6, which is the result you expect the demo to produce.

![image](https://user-images.githubusercontent.com/102368650/188265226-15eeffef-973f-4415-ad8a-5b3731059b6b.png)


Click Resume script execution Resume Script Execution.

In the Code Editor, replace line 31, var sum = addend1 + addend2, with var sum = parseInt(addend1) + parseInt(addend2).

Press Command + S (Mac) or Control + S (Windows, Linux) to save your change.

Click Deactivate breakpoints Deactivate breakpoints. Its color changes to blue to indicate that it's active. While this is set, DevTools ignores any breakpoints you've set.

Try out the demo with different values. The demo now calculates correctly.

![image](https://user-images.githubusercontent.com/102368650/188265838-e7dc2a30-4b0a-4cca-9d53-265c8b6aeefa.png)


