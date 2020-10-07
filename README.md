# Qik.js

####  Qik.js is a tiny expandable JS library that you can quickly install and customize


## Getting Started 

#### install the package with the simple command below

```
npm i qik.js
```

#### Example using the square function from qik.js library

const { square, cube, squareroot  } = require('qik.js')



console.log("Value of 3 to the square : ", square(3))




console.log("Value of 2 to the cube : ", cube(2))



console.log("Squareroot value of 9 : ", squareroot(9))



console.log("3 raised to the power of 2 : ", power(3,2))



```
"Value of 3 to the square : " : 9

"Value of 2 to the cube : " : 8

"Squareroot value of 9 : " : 3

"3 raised to the power of 2 : " 9 
```

## Reference

| function     | Description |
| -------------| ----------- |
| square       | Find the square of any integer e.g qik.square(2)  --> 4 |
| cube         | Find the cube of any integer e.g qik.square(2)  --> 8 |
| squareroot   | Find the squareroot of any integer e.g qik.squareroot(9)  --> 3 |
| power        | Find the value of 3 raised to the power 2 e.g qik.power(3,2)  --> 9 |


## To customize

Look for the index.js file and add your own custom functions to it

Example is shown below

```

module.exports.myExample = num => "My Number is : " + num;

```
