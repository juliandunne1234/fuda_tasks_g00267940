# Tasks Assessments for Fundamentals of Data Analysis:

|Name           |Email         |
|---------------|--------------|
|Julian Dunne   |G00267940@gmit.ie   

## Task 1: Write a python function called counts

The purpose of this task is to write a Python function called counts that takes a list as input and returns a dictionary of unique items in the list as keys and the number of times each item appears as values.

<b>Note:</b> The code should not depend on any module from the standard library1 or otherwise.

This notebook has 5 steps:
- Step 1) Initial code couldn't differetiate between integer, string and float.
- Step 2) Using try/except handling statement the code couldn't differetiate between floats and strings.
- Step 3) Using try statement inside another try statement resolved this. Step includes the code for creating the list.
- Step 4) Create the function counts that returns a dictionary with key, values for the elements in the list.
***

## Task 2: Write a pthon function called dicerolls

The purpose of this task is to write a Python function called dicerolls that simulates rolling dice. The function should take two parameters: the number of dice k and the number of times to roll the dice n. The function should simulate randomly rolling k dice n times, keeping track of each total face value. It should then return a dictionary with the number of times each possible total face value occurred.

<b>Note:</b> Any module from the Python standard library can be used.

This notebook includes several pieces of code that was used in Task 1:
- The user is first asked to input the number of dice and the number of times they are to be rolled.
- A function then takes these parameters and using the numpy random integers method, returns an array showing the combined values rolled by the dice for each roll.
- Using the function counts from task 1 it the code then returns a dictionary with each unique rolled value and the number of times it appeared.
- The values are then plotted in a histogram and shown to be normally distributed.
***

## Task 3: Write python code that simulates flipping a coin 100 times

The purpose of this task is to write some python code that simulates flipping a coin 100 times. Then run this code 1,000 times, keeping track of the number of heads in each of the 1,000 simulations. Select an appropriate plot to depict the resulting list of 1,000 numbers, showing that it roughly follows a bell-shaped curve.

<b>Note: </b>The numpy random binomial method was initially used to generate the random values as the author thought this is what was expected. The code has since been updated so as to not use this method.

The notebook has 7 steps:
- Step 1) Import the required libraries.
- Step 2) Code initially used random binomial method to generate values however this has now been changed to using nested functions to create the simulated values.
- Step 3) Create a dictionary that counts the number of occurences of each value generated in Step 2.
- Step 4) Determine the number of bins required to accurately plot the data in histogram form.
- Step 5) Generate a histogram of the data.
- Step 6) Plot the distribution showing that it follows a bell shaped curve.
- Step 7) Perfrom statistical analysis on data whereby the mean and the 50th percentile values should be very similiar if data is normally distributed.