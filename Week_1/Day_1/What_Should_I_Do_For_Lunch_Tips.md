### Tips

Try experimenting with the comparison operators (`<`, `>`, `===`, etc.) in the node REPL, which you can launch using the `node` command in Vagrant.

Work on your code iteratively – that means in small pieces. 

To help you figure out how to use `hungry` and `availableTime` inside your function, try outputting their values to the Terminal as follows.

```javascript
function whatToDoForLunch(hungry, availableTime) {
  console.log("hungry is", hungry);
  console.log("availableTime is", availableTime);
}
```

#### Avoid using 'else'

There's a way to complete the assignment without using `else`. By making your first conditional check if something is not true, you can return sooner and have cleaner code. All other conditionals do not need an else if you use the proper condition statement and the `return` properly.