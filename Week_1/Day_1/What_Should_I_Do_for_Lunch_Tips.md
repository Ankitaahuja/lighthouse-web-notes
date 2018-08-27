### Tips

Try experimenting with the comparison operators (`<`, `>`, `===`, etc.) in the node REPL, which you can launch using the `node` command in Vagrant.

Work on your code iteratively – that means in small pieces. 

To help you figure out how to use `hungry` and `availableTime` inside your function, try outputting their values to the Terminal as follows.

```javascript
function whatToDoForLunch(hungry, availableTime) {
  if (hungry === false){
    console.log("Get back to work");
  }
  else if (hungry === true && availableTime < 20){
    console.log("Pick something up and eat it in the lab.");
  }
  else if (hungry === true && availableTime <= 30){
    console.log("you deserve a break and could try a place in Gastown");
  }
  else {
    console.log(" You in a bootcamp, you should reconsider how much time you actually have to spare");
  }
}
```