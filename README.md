# Programming Exercise

Your task is to figure out how this code works.

* Come with a test input for the function.
* Trace the flow of the program with your test input **without running the code**, keeping track of all of the variables and transformations until you can determine the output.
* Keep coming up with new inputs until you're confident until you're confident that you know how the function works.
* Write a summary of what the function does.

```js
function (user){
  if (user.isActive){
    return `Welcome back, ${user.username}!`
  } else {
    return `Hey ${user.username}! Would you like to renew your subscription?`
  }
}
```

| Input  | Output                                                      |
| -----  | ------------------------------------------------------------|
| {Sam } | 'Welcome back, ladiesman217!'                               |
| {John} | 'Hey Johnboy21! Would you like to renew your subscription?' |
| {Stu } | 'Welcome back, Stutheman415!'                               |

<table>
  <tr>
    <th>What does this program do?</th>
    <td>This program determines if a user is active and if so, it stores in the return the appropriate response with their user name listed. If they are inactive it prompts them to do a renewal.</td>
  </tr>
</table>

## Rubric

* Contains a plausible collection of test cases
* Outputs are accurately derived from inputs
* Summary is plausible
