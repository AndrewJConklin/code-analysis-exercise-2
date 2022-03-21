# Programming Exercise

Your task is to figure out how this code works.

* Come with a test input for the function.
* Trace the flow of the program with your test input **without running the code**, keeping track of all of the variables and transformations until you can determine the output.
* Keep coming up with new inputs until you're confident until you're confident that you know how the function works.
* Write a summary of what the function does.

```js
function (floor){
  if (floor <= 0){
    return floor
  }

  let offset = 1
  if (floor >= 13){
    offset = 2
  }

  return floor - offset
}
```

| Input | Output |
| 0     |   0    |
| 1     |   0    |
|  5    |   4    | 
|  15   |   13   | 
|  -5   |   -5   | 
|  12   |   11   | 
|  13   |   11   | 

<table>
  <tr>
    <th>What does this program do?</th>
    <td>This programs takes a number as an input and returns a value that depends on what number was inputted. If the number is 0 or below, it returns that number unchanged. If the number is 1 through 12, it returns the number - 1. Finally if the number is 13 or greater, it returns the number -2. </td>
  </tr>
</table>

## Rubric

* Contains a plausible collection of test cases
* Outputs are accurately derived from inputs
* Summary is plausible
