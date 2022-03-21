# Programming Exercise

Your task is to figure out how this code works.

* Come with a test input for the function.
* Trace the flow of the program with your test input **without running the code**, keeping track of all of the variables and transformations until you can determine the output.
* Keep coming up with new inputs until you're confident until you're confident that you know how the function works.
* Write a summary of what the function does.

```js
function (currentColor){
  if (currentColor === "green"){
    nextColor = "yellow"
  } else if (currentColor === "yellow"){
    nextColor = 'red'
  } else if (currentColor === "red"){
    nextColor = 'green'
  }

  return nextColor
}
```

| Input | Output    |
| ----- | ----------|
| red   | {'green'} |  
| green | {'yellow'}| 
| blue  | undefined | 

<table>
  <tr>
    <th>What does this program do?</th>
    <td> If the input color is green, yellow, or red the output will return yellow, red, or green color. If the input is not one of the 3 colors the output will return as undefined.</td>
  </tr>
</table>

## Rubric

* Contains a plausible collection of test cases
* Outputs are accurately derived from inputs
* Summary is plausible
