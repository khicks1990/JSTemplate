# JS-Chapter2
JavaScript Chapter 2 Programming Assignment

In this project you will create an application to convert temperature readings between Fahrenheit and Celsius and between Celsius and Fahrenheit. The formula to convert a Fahrenheit temperature to the Celsius scale is

Celsius = (Fahrenheit − 32)/1.8

and the formula to convert a Celsius temperature to the Fahrenheit scale is

Fahrenheit = Celsius × 1.8 + 32

Users will enter a value in a Celsius or Fahrenheit input box, press the Tab key and have the other input box automatically show the temperature reading in the other scale. A preview of the completed page is shown.

![image](https://github.com/user-attachments/assets/024767dd-2a8d-4be8-9817-c92b4ca6d3ef)


Do the following:

Use your code editor to open the index.html and script.js files. Enter your name and the date in the comment section of each file. Commit your changes.

Go to the index.html file in your code editor and in the head section add a script element to load the script.js file. Include the defer attribute to defer loading the external script file until the entire page is loaded. Study the contents of the HTML file and then save your changes.

Go to the script.js file in your code editor. Create a function named FahrenheitToCelsius() containing a single parameter named degree. Insert a statement that returns the value of degree minus 32 and then divided by 1.8.

Create a function named CelsiusToFahrenheit() containing a single parameter named degree. Insert a statement that returns the value of degree multiplied by 1.8 plus 32.

Add an onchange event handler to the element with the id “cValue”. Attach an anonymous function to the event handler and within the anonymous function do the following:

Declare a variable named cDegree equal to the value of the element with the id “cValue”.

Set the value of the element with the id “fValue” to the value returned by the CelsiusToFarenheit() function using cDegree as the parameter value.

Add an onchange event handler to the element with the id “fValue”. Attach an anonymous function to the event handler and within the anonymous function do the following:

Declare a variable named fDegree equal to the value of the element with the id “fValue”.

Set the value of the element with the id “cValue” to the value returned by the FarenheitToCelsius() function using fDegree as the parameter value.

Commit your changes to the file.

Open index.html in your web browser. Verify that when you enter 45 in the Temp in C° box and press Tab a value of 113 appears in the Temp in F° box. Verify that when you enter 59 in the Temp in F° box and press Tab a value of 15 appears in the Temp in C° box.
