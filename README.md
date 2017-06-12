## Scope, hoisting and compartmentalization

### Answer the following:
In you own words, explain the concepts of scope, hoisting, compartmentalization.

Scope determines which code is run (or accessible) at what time. Hoisting is a property in Javascript that moves variables to the top of the scope they are contained in. Compartmentalization is the use of scope to contain certain variables from effecting the rest of the code.

### Provide examples for all three, below:

#### Scope:
function hello(){
  var name: Ian;
}
console.log()

Console.log is outside of the functions local scope.
#### Hoisting:
function hello(){
  var name: Ian;
}

Hoisting will move the variable to the top.
#### Compartmentalization:

function hello(){
  var name: Ian;
}
console.log(Ian)

Ian cant be reached because it is outside the local scope of the function.
