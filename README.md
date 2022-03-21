# Programming Exercise

Your task is to figure out how this code works.

* Come with a test input for the function.
* Trace the flow of the program with your test input **without running the code**, keeping track of all of the variables and transformations until you can determine the output.
* Keep coming up with new inputs until you're confident until you're confident that you know how the function works.
* Write a summary of what the function does.

```js
function (person, petName){
  for (dog in person.dogs){
    if (dog.name === petName){
      return dog
    }
  }
}
```

| Input | Output |
| ----- | ------ |
|   `Angela = {name: "Angela" , dogs: ["Skye' , "Olaf", "Timmy", "Lego"]}, "Olaf"`    |    "Olaf"    | 
|   `Cindi = {name: "Cindi", dogs : ["Ronon" , "Sasha"]}, "Ronon"`  |   "Ronon"     | 
|   `Cindi = {name: "Cindi", dogs : ["Ronon" , "Sasha"]}, "Sasha"`    |    "Sasha"    | 

<table>
  <tr>
    <th>What does this program do?</th>
    <td>Searches for a dog's name though a list of dog's names assigned to a person</td>
  </tr>
</table>

## Rubric

* Contains a plausible collection of test cases
* Outputs are accurately derived from inputs
* Summary is plausible
