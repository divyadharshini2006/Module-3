# Exp.No:3e
## SEB - SUM OF EVEN NUMBERS FROM LIST

### AIM  
To Write a python program to display the sum of all the values which are ending with 2 from a list

### ALGORITHM

1. Begin the program.
2. Use eval() to get a list a from the user.
3. Initialize sum to 0.
4. Use a for loop to iterate through each element in the list a:
5. If the element is even (i.e., i % 2 == 0), add it to sum.
6. Print the total sum of the even numbers in the list.
7. Terminate the program.
 
### PROGRAM
```
a=eval(input())
sum=0
for i in a:
    if i%2==0:
        sum+=i
print("Sum=",sum)
```
### OUTPUT
![Screenshot 2025-04-27 155706](https://github.com/user-attachments/assets/726bcdbb-d2a9-4b30-b199-2120f9bfd7ff)

### RESULT
Thus a python program to display the sum of all the values which are ending with 2 from a list has been successfully implemented.

