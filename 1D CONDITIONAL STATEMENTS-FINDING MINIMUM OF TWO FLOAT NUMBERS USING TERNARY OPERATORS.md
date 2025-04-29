## Experiment No: 1d – Conditional Statements – Finding Minimum of Two Float Numbers Using Ternary Operator

## AIM 
To write a Python program to find the minimum of two float numbers using a conditional expression (ternary operator).

## ALGORITHM  
1.Start the program
Initialize the Python environment and create a new script to take inputs and process the logic.
2.Input the two float numbers
Take two float numbers as input from the user using the input() function and convert them to float type using float().
3.Use the ternary operator for comparison
Use the ternary operator (conditional expression) to check which number is smaller:
minimum = num1 if num1 < num2 else num2
4.Display the result
Print the result showing the minimum of the two numbers using the print() function.

## PROGRAM
x=float(input())
y=float(input())
mini=(x if(x<y) else y)
print(f"The minimum of {x} and {y} is {mini}")

## OUTPUT
![image](https://github.com/user-attachments/assets/30c8f7ae-8632-4ac1-b397-1375c7741c50)

## RESULT
Thus,Python program to find the minimum of two float numbers using a conditional expression (ternary operator) was implemented and successfully executed.
