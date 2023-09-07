
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
          document.writeln(`THE SUM OF ${a} AND ${b} IS  ${sum}` + "<br>");
          document.writeln(`THE SUBTRACTION OF ${a} AND ${b} IS ${sub}` + "<br>");
          document.writeln(`THE MULTIPLICATION OF ${a} AND ${b} IS ${mul}` + "<br>");
          document.writeln(`THE DIVISION OF ${a} AND ${b} IS ${div}` + "<br>");
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


## TASK 4: Cost of one movie ticket is 600 PKR. Write a script to store ticket price in a variable & calculate the cost of buying 5 tickets to a movie.
### CODE:
    <script>
      var cost = 600;
      var tickets = parseInt(prompt("ENTER THE NUMBER OF TICKETS??"));
      document.writeln(`TOTAL COST TO BY ${tickets} TO A MOVIE IS ${cost}PKR`);
    </script>
### OUTPUT:
![image](https://github.com/RizwanAnsar2004/SMIT-JS-2/assets/131580981/c2bc610d-e8ad-40f5-aa60-44cd088cb3f1)
![image](https://github.com/RizwanAnsar2004/SMIT-JS-2/assets/131580981/faf67178-7387-443f-80a3-08309e4c61f6)


## TASK 5: Write a script to display multiplication table of any number in your browser
### CODE:
    <script>
      for (let index = 1; index <= 10; index++) {
        let mul = 4 * index;
        document.write("4 x " + index + " = " + mul + "<br>");
      }
    </script>
### OUTPUT:
![image](https://github.com/RizwanAnsar2004/SMIT-JS-2/assets/131580981/5454775a-4187-46a2-a51a-97e38fc36f4a)



## TASK 6: The Temperature Converter: It’s hot out! Let’s make a converter based on the steps here.a. Store a Celsius temperature into a variable.b. Convert it to Fahrenheit & output “NNoC is NNoF”.c. Now store a Fahrenheit temperature into a variable.d. Convert it to Celsius & output “NNoF is NNoC”.
### CODE:
     <script>
       let celsisus=parseFloat(prompt("ENTER TEMPERATURE IN CELSIUS:"));
       let fahrenheit=parseFloat(prompt("ENTER TEMPERATURE IN FAHRENHEIT:"));;
       let CtoF=(fahrenheit-32)*5/9;
      let FtoC=(celsisus*9/5)+32;
      document.write(`${celsisus}`+"<sup>o</sup>" +`C is ${CtoF}`+"<sup>o</sup> F"+ "<br>");
      document.write(`${fahrenheit}`+"<sup>o</sup>" +`C is ${FtoC}`+"<sup>o</sup> F");
    </script>
### OUTPUT:
![image](https://github.com/RizwanAnsar2004/SMIT-JS-2/assets/131580981/c66086ca-f2c4-48a4-8d34-14140daba2e7)
![image](https://github.com/RizwanAnsar2004/SMIT-JS-2/assets/131580981/d6eea3db-dade-4bfd-9aad-02dcabcc10c7)
![image](https://github.com/RizwanAnsar2004/SMIT-JS-2/assets/131580981/240c817b-678b-4aae-87eb-e668330e552e)



## TASK 7: Write a program to implement checkout process of a shopping cart system for an e-commerce website. Store the following in variablesa. Price of item 1 b. Price of item 2 c. Ordered quantity of item 1 d. Ordered Quantity of item 2 e. Shipping chargesCompute the total cost & show the receipt in your browser.
### CODE:
    <script>
        let item1=650,item2=100;
        let ship=100;
        document.write("<h1>Shopping Cart</h1><br><br>");
        let quantity1=parseInt(prompt("ENTER THE QUANTITY OF ITEM 1"));
        let quantity2=parseInt(prompt("ENTER THE QUANTITY OF ITEM 2"));

        document.write(`PRICE OF ITEM 1 is ${item1}`+"<br>");
        document.write(`QUANTITY OF ITEM 1 is ${quantity1}`+"<br>");
        document.write(`PRICE OF ITEM 2 is ${item2}`+"<br>");
        document.write(`QUANTITY OF ITEM 1 is ${quantity2}`+"<br>");
        document.write("Shipping Charges: "+ship+"<br>"+"<br>"+"<br>");
        document.write(`TOTAL COST OF YOUR ORDER is ${(item1*quantity1)+(item2*quantity2)+ship}`);

    </script>
### OUTPUT:
![image](https://github.com/RizwanAnsar2004/SMIT-JS-2/assets/131580981/3a6bece4-f267-45e4-b57c-e1448ce4909a)


## TASK 8:Store total marks & marks obtained by a student in 2 variables. Compute the percentage & show the result in your browser

### CODE:
    <script>
       document.write("<h1>MARK SHEET</h1><br><br>")
       let total=parseInt(prompt("ENTER TOTAL MARKS"));
       let obtained=parseInt(prompt("ENTER OBTAINED MARKS"));
       document.write(`TOTAL MARKS : ${total}`);
       document.write(`OBTAINED MARKS : ${obtained}`);
       document.write(`PERCENTAGE : ${(obtained/total)*100}`);
    </script>
### OUTPUT:
![image](https://github.com/RizwanAnsar2004/SMIT-JS-2/assets/131580981/8e8dbd32-9b05-44da-916a-d5ba0f0a98b7)
![image](https://github.com/RizwanAnsar2004/SMIT-JS-2/assets/131580981/08ab9dd2-8557-4200-9953-1eee4dee1c08)
![image](https://github.com/RizwanAnsar2004/SMIT-JS-2/assets/131580981/76a85ea4-ba7c-4787-ae23-995fdc621c14)


## TASK 9:Assume we have 10 US dollars & 25 Saudi Riyals. Write a script to convert the total currency to Pakistani Rupees. Perform all calculations in a single expression.

### CODE:
    <script>
        document.write("<h1>CURRENCY IN PKR</h1><br><br>")
       let dollar=parseInt(prompt("ENTER US DOLLARS"));
       let riyal=parseInt(prompt("ENTER RIYAL"));
       let pkr=(dollar*305)+(riyal*81);
       document.write(`TOTAL CURRENCY IN PKR : ${pkr}`+"<br>");
    </script>
### OUTPUT:
![image](https://github.com/RizwanAnsar2004/SMIT-JS-2/assets/131580981/2d091e07-31ee-44d6-985f-ee3e8fb89466)
![image](https://github.com/RizwanAnsar2004/SMIT-JS-2/assets/131580981/d81d5973-b078-4abf-ac5f-1ed565946d1a)
![image](https://github.com/RizwanAnsar2004/SMIT-JS-2/assets/131580981/44bd4bd9-3ac6-4396-81b6-c8cd3c795264)


## TASK 10: Write a program to initialize a variable with some number and do arithmetic in following sequence: a. Add 5 b. Multiply by 10 c. Divide the result by 2 Perform all calculations in a single expression
### CODE:
    <script>
        let variable=10;
        variable=((variable+5)*10)/2;
        console.log("THE ANSWER IS "+variable);
    </script>
### OUTPUT:
![image](https://github.com/RizwanAnsar2004/SMIT-JS-2/assets/131580981/fdb8f437-7c13-4736-87c0-7d0effad6855)


## TASK 11:The Age Calculator: Forgot how old someone is? Calculate it! a. Store the current year in a variable. b. Store their birth year in a variable. c. Calculate their 2 possible ages based on the stored values.
### CODE:
     <script>
        document.write("<h1>AGE CALCULATOR</h1><br><br>")
       let c_year=parseInt(prompt("ENTER CURRENT YEAR"));
       let b_current=parseInt(prompt("ENTER YOUR BIRTH YEAR"));
       document.write(`CURRENT YEAR: ${c_year}`+"<br>");
       document.write(`BIRTH YEAR : ${b_current}`+"<br>");
       document.write(`YOUR AGE : ${b_current-c_year}`+"<br>");
    </script>
### OUTPUT:

![image](https://github.com/RizwanAnsar2004/SMIT-JS-2/assets/131580981/658e518f-58fb-4cc1-8a49-bfb451c445f1)
![image](https://github.com/RizwanAnsar2004/SMIT-JS-2/assets/131580981/b909829e-08a2-4240-b2b2-a1b4b91c3ac5)
![image](https://github.com/RizwanAnsar2004/SMIT-JS-2/assets/131580981/bad44bf0-64b2-42d5-b5db-3ccf1bfbe653)


## TASK 12:The Geometrizer: Calculate properties of a circle. a. Store a radius into a variable.b. Calculate the circumference based on the radius, and output “The circumference is NN”. (Hint : Circumference of a circle = 2 π r , π = 3.142) Calculate the area based on the radius, and output “The area is NN”
### CODE:
    <script>
      document.write("<h1>The Geometrizer</h1><br><br>");
      let radius = parseFloat(prompt("ENTER RAIUS OF CIRCLE"));
      let circum=2*Math.PI*radius;
      let area=Math.PI*Math.pow(radius,2);
      document.write(`RADIUS OF CIRCLE: ${radius}`+"<br>");
      document.write(`CIRCUMFERENCE OF CIRCLE: ${circum}`+"<br>");
      document.write(`AREA OF CIRCLE: ${area}`+"<br>");
    </script>
### OUTPUT:

![image](https://github.com/RizwanAnsar2004/SMIT-JS-2/assets/131580981/5b2e22c6-b30d-4fb9-a85a-2b9ce0149f22)
![image](https://github.com/RizwanAnsar2004/SMIT-JS-2/assets/131580981/cee86946-c586-46ab-9dec-5cb167c1b2a5)


## TASK 13:The Lifetime Supply Calculator: Ever wonder how much a “lifetime supply” of your favorite snack is? Wonder no more. a. Store your favorite snack into a variable b. Store your current age into a variable. c. Store a maximum age into a variable. d. Store an estimated amount per day (as a number). e. Calculate how many would you eat total for the rest of your life.Output the result to the screen like so: “You will need NNNN to last you until the ripe old age of NN”.
### CODE:
    <script>
      document.write("<h1>The Lifetime Supply Calculator</h1><br><br>");
      let snack="CHOCOLATE";
      let c_age=parseInt(prompt("ENTER YOUR CURRENT AGE"));
      let m_age=parseInt(prompt("ENTER YOUR MAXIMUM AGE"));
      let consumption=parseInt(prompt("ENTER CONSUMPTION PER DAY"));
      let days=(m_age-c_age)*365;
      let total=days*consumption;
      document.write(`FAVOURITE SNACK: ${snack}`+"<br>");
      document.write(`CURRENT AGE: ${c_age}`+"<br>");
      document.write(`ESTIMATED MAXIMUM AGE: ${m_age}`+"<br>");
      document.write(`CONSUMPTION PER DAY: ${consumption}`+"<br>");
      document.write(`YOU WILL NEED ${total} CHOCOLATE TO LAST UNTIL THE RIPE OLD AGE OF ${m_age}`);
    </script>
### OUTPUT:
![image](https://github.com/RizwanAnsar2004/SMIT-JS-2/assets/131580981/fd46c316-5a7b-4dd9-919e-ee7c1f98de6d)
![image](https://github.com/RizwanAnsar2004/SMIT-JS-2/assets/131580981/21d19dae-82f2-4099-b724-9aad11723ee7)
![image](https://github.com/RizwanAnsar2004/SMIT-JS-2/assets/131580981/de7ecb57-075f-4cfe-acd5-02bc7dd43c90)
![image](https://github.com/RizwanAnsar2004/SMIT-JS-2/assets/131580981/748d508f-f83e-40d8-8760-0c73e2ea4f5d)
