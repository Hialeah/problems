<h2 id="31"> 31. Areas of Rectangles</h2>

The area of a rectangle is the rectangle’s length times its width. Write a program that asks for the length and width of two rectangles. The program should tell the user which rectangle has the greater area, or if the areas are the same.

- [ ] Answer in C++
- [ ] Answer in Java

<h2 id="32"> 32.  Mass and Weight</h2>

Scientists measure an object’s mass in kilograms and its weight in newtons. If you know an object’s mass, you can calculate its weight in newtons with the following formula: 

    weight = mass  - 9.8
    
Write a program that asks the user to enter an object’s mass, and then calculates and displays its weight. If the object weighs more than 1000 newtons, display a message indicating that it is too heavy. If the object weighs less than 10 newtons, display a message indicating that the object is too light.

- [ ] Answer in C++
- [ ] Answer in Java

<h2 id="33"> 33. Time Calculator</h2>

Write a program that asks the user to enter a number of seconds.

- There are 86400 seconds in a day. If the number of seconds entered by the user is greater than or equal to 86400, the program should display the number of days in that many seconds.
- There are 3600 seconds in an hour. If the number of seconds entered by the user is less than 86400, but is greater than or equal to 3600, the program should display the number of hours in that many seconds.
- There are 60 seconds in a minute. If the number of seconds entered by the user is less than 3600, but is greater than or equal to 60, the program should display the number of minutes in that many seconds.

- [ ] Answer in C++
- [ ] Answer in Java

<h2 id="34"> 34.  Bank Charges</h2>

A bank charges $10 per month plus the following check fees for a commercial checking account:

&nbsp;&nbsp;&nbsp;&nbsp;**$.10** each for fewer than **20** checks

&nbsp;&nbsp;&nbsp;&nbsp;**$.08** each for **20–39** checks

&nbsp;&nbsp;&nbsp;&nbsp;**$.06** each for **40–59** checks

&nbsp;&nbsp;&nbsp;&nbsp;**$.04** each for **60** or more checks

Write a program that asks for the number of checks written during the past month, then computes and displays the bank’s fees for the month.

*Input Validation:* Do not accept a negative value for the number of checks written.

- [ ] Answer in C++
- [ ] Answer in Java

<h2 id="35"> 35.  Geometry Calculator</h2>

Write a program that displays the following menu:

```
Geometry Calculator
1. Calculate the Area of a Circle
2. Calculate the Area of a Rectangle
3. Calculate the Area of a Triangle
4. Quit
Enter your choice (1-4):
```
If the user enters:

- **1** The program should ask for the radius of the circle and then display its area. Use 3.14159 for π.
- **2** The program should ask for the length and width of the rectangle, and then display the rectangle’s area.
- **3** The program should ask for the length of the triangle’s base and its height, and then display its area.
- **4** The program should end.

#### *Input Validation:*

Display an error message if the user enters a number outside the range of 1 through 4 when selecting an item from the menu. 

Do not accept negative values for the circle’s radius, the rectangle’s length or width, or the triangle’s base or height.


- [ ] Answer in C++
- [ ] Answer in Java

<h2 id="36"> 36.  Running the Race</h2>

Write a program that asks for the names of three runners and the time it took each of them to finish a race. The program should display who came in first, second, and third place. Think about how many test cases are needed to verify that your problem works correctly. (That is, how many different finish orders are possible?)
Input Validation: Only accept positive numbers for the times.

- [ ] Answer in C++
- [ ] Answer in Java

<h2 id="37"> 37. Personal Best</h2>

Write a program that asks for the name of a pole vaulter and the dates and vault heights (in meters) of the athlete’s three best vaults. It should then report in height order (best first), the date on which each vault was made, and its height.
Input Validation: Only accept values between 2.0 and 5.0 for the heights.


- [ ] Answer in C++
- [ ] Answer in Java

<h2 id="38"> 38. Body Mass Index</h2>

Write a program that calculates and displays a person’s body mass index (BMI). The BMI is often used to determine whether a person with a sedentary lifestyle is overweight or underweight for his or her height. A person’s BMI is calculated with the following formula:

        BMI = weight × 703 / height2

where weight is measured in pounds and height is measured in inches. The program should display a message indicating whether the person has optimal weight, is underweight, or is overweight. A sedentary person’s weight is considered to be optimal if his or her BMI is between 18.5 and 25. If the BMI is less than 18.5, the person is considered to be underweight. If the BMI value is greater than 25, the person is considered to be overweight.


- [ ] Answer in C++
- [ ] Answer in Java

<h2 id="39"> 39.  Fat Gram Calculator</h2>

Write a program that asks for the number of calories and fat grams in a food. The program should display the percentage of calories that come from fat. If the calories from fat are less than 30 percent of the total calories of the food, it should also display a message indicating the food is low in fat.

- One gram of fat has 9 calories, so
- Calories from fat = fat grams * 9
- The percentage of calories from fat can be calculated as

       Calories from fat ÷ total calories


#### **Input Validation:** 

Make sure the number of calories is greater than 0 and the number of fat grams is 0 or more.

Also, the number of calories from fat cannot be greater than the total number of calories. 

If that happens, display an error message indicating that either the calories or fat grams were incorrectly entered.



- [ ] Answer in C++
- [ ] Answer in Java

<h2 id="40"> 40.  Characters for the ASCII Codes</h2>

Write a program that uses a loop to display the characters for each ASCII code 32 through 127. Display 16 characters on each line with one space between characters.


- [ ] Answer in C++
- [ ] Answer in Java
