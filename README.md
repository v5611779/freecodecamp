# freecodecamp

.pop()
.shift()
.push()
.unshift()


function myLocalScope() {
  var myVar;
  console.log('inside myLocalScope', myVar);
}

myLocalScope();

function greet(name){
  return `Hello, ${name} how are you doing today?`;
}
