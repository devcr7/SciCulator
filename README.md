# SciCulator
A Scientific Calculator App

The app solves the arithmetic, trigonometric and logarithmic expressions.

Data types used in the MainActivity include:
1. Buttons: Multiple objects of this data type have been created inorder to take the value from the user as indicated in the text of the respected button.
2. TextView: Two objects of this class have been created, one to display the final result and the other to show the current working expression.
3. String: Stores the value of pie upto 18 decimal places.

Functions/methods used in the MainActivity include:                                                                              
1. onCreate(Bundle obj): This function itself links the main xml file to the content view, besides this it has been used to call other functions as soon as the app starts.
2. OnPress(): This is a non return type public function which stores all the 'onClickListeners' for the buttons and displays the required data in both the text views, it explicitly calls the 'evaluate' method and displays the result as soon as the 'equal' button is pressed on the UI.
3. evaluate(obj): It performs all the complex calculations and finally returns the answer as double by taking a string object as a parameter.

The defined OnPress function also checks if there is an integer overflow, wrong parenthesization, invalid expression etc., and displays the corresponding required warning/message so that the expression can be correctly re-entered.

The app icon has been generated with the help of the "Launcher icon generator" and the icon image has been taken from "Free stock images".

Screenshot:


![Screenshot_2021-12-09-05-25-38-325_com example sciculator](https://user-images.githubusercontent.com/61392760/145310525-d71118a6-d34d-4048-ac83-38e9436608b9.jpg)
