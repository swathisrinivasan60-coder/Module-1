## Experiment No: 1d – Conditional Statements- Write a python program to find the smallest among three Integer Numbers

## AIM  
The aim of this program is to determine the smallest integer among three given numbers.
## ALGORITHM  

1.Define a function find_smallest that takes three parameters (num1, num2, num3). 2.Initialize a variable smallest with the value of num1 (assuming num1 is the smallest initially). 3.Check if num2 is smaller than smallest. If so, update smallest to num2. 4.Check if num3 is smaller than smallest. If so, update smallest to num3. 5.Return the variable smallest. 6.Use the function with example values to demonstrate its functionality.

## PROGRAM
```
a=int(input())
b=int(input())
c=int(input())
if a<b:
big=a
else:
big=b
if c<big:
big=c
print("The Smallest of the three a=",a,"b=",b,"c=",c,"is",big)

```

## OUTPUT

<img width="915" height="250" alt="image" src="https://github.com/user-attachments/assets/d3f2da80-9b31-4fd6-9836-4ec7ea859b4b" />

## RESULT
Thus the given program implemented and executed successfully.
