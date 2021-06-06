# Operators 
* ### Arithmetic Operators (+, -, *, /+,−,∗,/)**
```javascript

    console.log("****Arithmetic Operators****\n")
    console.log("2 + 3 = " + (2 + 3))
    console.log("2 - 3 = " + (2 - 3))
    console.log("2 + 3 = " + (2 * 3))
    console.log("6 + 3 = " + (6 / 3))
    console.log("7 + 3 = " + (7 / 3))
```
+ ### Assignment Operators (=, +=, -=, *=)**
  ```javascript
   
    console.log("\n****Assignment Operators****\n")
    var x = 3;
    console.log("x = " + x)
    console.log("x += 1 gives x = " + (x+=1)) // adds 1
    console.log("x -= 1 gives x = " + (x-=1)) // subtracts 1
    console.log("x *= 3 gives x = " + (x*=3)) // multiplies 3 with x
  ```
  + ### Logical Operators (&&, ||, ! $)
```javascript
        console.log("\n****Logical Operators****\n")
        console.log("1 OR 1 = " + (1 || 1)) // 1 OR 1
        console.log("1 OR 0 = " + (1 || 0)) // 1 OR 0
        console.log("0 OR 0 = " + (0 || 0)) // 0 OR 0
        console.log("1 AND 1 = " + (1 && 1)) // 1 AND 1
        console.log("1 AND 0 = " + (1 && 0)) // 1 AND 0
        console.log("0 AND 0 = " + (0 && 0)) // 0 AND 0
        console.log(!true)  // NOT TRUE
        console.log(!1)     // NOT TRUE
        console.log(!false) // NOT FALSE
        console.log(!0)     // NOT FALSE
```
### Destructuring assignment
The **destructuring assignment** syntax is a JavaScript expression that makes it possible to unpack values from arrays, or properties from objects, into distinct variables.
```javascript
let a, b, rest;
[a, b] = [10, 20];

console.log(a);
// expected output: 10

console.log(b);
// expected output: 20

[a, b, ...rest] = [10, 20, 30, 40, 50];

console.log(rest);
// expected output: Array [30,40,50]
```

### Comparison Operators

|Operator|Description|Example|
|---------|-----------|-------|
|==|Equal to: true if the operands are equal|5==5; //true|
|!=|Not equal to: true if the operands are not equal|5!=5; //false|
|===|Strict equal to: true if the operands are equal and of the same type|5==='5'; //false|
|!==|Strict not equal to: true if the operands are equal but of different type or not equal at all|5!=='5'; //true|
|>|Greater than: true if the left operand is greater than the right operand|3>2; //true|
|>=|Greater than or equal to: true if the left operand is greater than or equal to the right operand|3>=3; //true|
|<|	Less than: true if the left operand is less than the right operand|	3<2; //false|
|<=|Less than or equal to: true if the left operand is less than or equal to the right operand|or equal to the right operand	2<=2; //true|

# Loops
> Loops are used in JavaScript to perform repeated tasks based on a condition. Conditions typically return true or false when analysed. A loop will continue running until the defined condition returns false.

### for loop
* Syntax
**for ([initialization]); [condition]; [final-expression]) {
   // statement
}**

> * The javascript for statement consists of three expressions and a statement:

##### Example :
```javascript
for (var i = 0; i < 9; i++) {
   console.log(i);
}

output:
0
1
2
3
4
5
6
7
8
```
### while loop
> * The while loop starts by evaluating the condition. If the condition is true, the statement(s) is/are executed. If the condition is false, the statement(s) is/are not executed. After that, while loop ends.

```javascript
while (condition)

{

  statement(s);

}
```
##### Example:
```javascript
    var i = 1;
    while (i < 10) 
    {
      console.log(i);
       i++; // i=i+1 same thing
    }

    Output:
    1 
    2 
    3 
    4
    5
    6
    7
    8
    9
```