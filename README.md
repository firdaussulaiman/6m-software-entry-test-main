# 6m-software-entry-test-main
/*
    Task 1
    - Create a function that would swap the value of x and y using only x and y as variables.
    - x and y must be numeric.
    - return -1 if x and y is not numeric.
    - print the swapped values in the console

    Task 2
    - invoke the function "swap"
*/

  
    // Task 1: Add code here  

    
let x = prompt('Enter the first variable: ');
let y = prompt('Enter the second variable: ');


//create a temporary variable
let temp;


//swap variables
function swap(x, y){ 
return x = y
}
temp = x;
x = y;
y = temp;

  if (isNaN(x)) {
            alert((x = -1,y = -1),"x = -1,y = -1")
        } else if (isNaN(y)) {
            alert((x = -1,y = -1),"x = -1,y = -1")
        } 

    
console.log(`The value of x after swapping: ${x}`);
console.log(`The value of y after swapping: ${y}`);



// Task 2: Add code here
console.log(swap(x,y))
module.exports = swap;
