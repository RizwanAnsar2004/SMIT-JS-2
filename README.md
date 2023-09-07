
# SMIT JS 2 ASSIGNMENT:

## TASK 1: Write a program that take two numbers & add them in a new variable. Show the result in your browser.

### CODE:
  <script>


        let a = parseInt(prompt("ENTER FIRST NUMBER"));
      let b = parseInt(prompt("ENTER SECOND NUMBER"));
let sum=a+b;
document.writeln(`THE SUM OF ${a} AND ${b} IS ${sum}`);
    </script>

### OUTPUT:

![image](https://github.com/RizwanAnsar2004/SMIT-JS-2/assets/131580981/82ab9647-ad35-4cc9-9cc0-1a4512f19a22)
![image](https://github.com/RizwanAnsar2004/SMIT-JS-2/assets/131580981/73eb1088-52c3-4bf7-9558-0422019d4677)
![image](https://github.com/RizwanAnsar2004/SMIT-JS-2/assets/131580981/1c69aa0b-a8cc-4149-991e-eff40949f725)


## TASK 2: Repeat task1 for subtraction, multiplication, division & modulus.

### CODE:
<script>
      let a = parseInt(prompt("ENTER FIRST NUMBER"));
      let b = parseInt(prompt("ENTER SECOND NUMBER"));
      let sum = a + b;
      let sub = a - b;
      let mul = a * b;
      let div = a / b;
      document.writeln(`THE SUM OF ${a} AND ${b} IS  ${sum}`+"<br>");
      document.writeln(`THE SUBTRACTION OF ${a} AND ${b} IS ${sub}`+"<br>");
      document.writeln(`THE MULTIPLICATION OF ${a} AND ${b} IS ${mul}`+"<br>");
      document.writeln(`THE DIVISION OF ${a} AND ${b} IS ${div}`+"<br>")
    </script>
### OUTPUT:

![image](https://github.com/RizwanAnsar2004/SMIT-JS-2/assets/131580981/7a858344-a7ff-4a52-8a8b-c16812fbee17)
![image](https://github.com/RizwanAnsar2004/SMIT-JS-2/assets/131580981/9c4e24f0-bc75-47b5-ad5a-ff9653ddd203)
![image](https://github.com/RizwanAnsar2004/SMIT-JS-2/assets/131580981/b87902ec-6f96-4b4b-bda0-0d8b46cd48aa)

## TASK 3:Do the following using JS Mathematic Expressions a. Declare a variable. b. Show the value of variable in your browser like “Value after variable declaration is: ??”. c. Initialize the variable with some number. d. Show the value of variable in your browser like “Initial value: 5”. e. Increment the variable. f. Show the value of variable in your browser like “Value after increment is: 6”. g. Add 7 to the variable. h. Show the value of variable in your browser like “Value after addition is: 13”. i. Decrement the variable. j. Show the value of variable in your browser like “Value after decrement is: 12”. k. Show the remainder after dividing the variable’s value by 3.l. Output : “The remainder is : 0”.

### CODE:
    <script>
      var variable;
      document.write(`THE VALUE OF VARIABLE IS ${variable}` + "<br>");
      variable = 5;
      document.write(`THE INITIAL VALUE OF VARIABLE IS ${variable}` + "<br>");
      variable++;
      document.write(`THE INCREMENTED VALUE OF VARIABLE IS ${variable}` + "<br>");
      variable += 7;
      document.write(`THE ADDED VALUE OF VARIABLE IS ${variable}` + "<br>");
      variable--;
      document.write(`THE DECREMENTED VALUE OF VARIABLE IS ${variable}` + "<br>");
      var remainder = variable % 3;
      document.write(`THE REMAINDER  IS ${remainder}` + "<br>");
    </script>
### OUTPUT:
![image](https://github.com/RizwanAnsar2004/SMIT-JS-2/assets/131580981/818d7ad9-6c62-44c8-9c0e-155c5a92e14c)
