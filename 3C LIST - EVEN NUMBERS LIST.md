# Exp.No:3c
## LIST - ADDING THE VALUES FROM THE LIST

### AIM  
To Write a python program to display the product of all the values which are ending with 2 from a list.

### ALGORITHM

1. Begin the program.
2. Use eval() to get a list l from the user.
3. Initialize sum to 1.
4. Use a for loop to iterate through each element of the list l:
5. If the current element l[i] has a last digit of 2 (i.e., l[i] % 10 == 2), multiply sum by l[i].
6. Print the product of the elements that meet the condition.
7. Terminate the program.
   
### PROGRAM
```
l=eval(input())
sum=1
for i in range(0,len(l)):
    if l[i]%10==2:
        sum*=l[i]
print("Product= {}".format(sum))
```
### OUTPUT
![Screenshot 2025-04-27 153505](https://github.com/user-attachments/assets/b9203b6e-1f92-4c95-a2e1-caf65ab36414)

### RESULT
Thus a python program to display the product of all the values which are ending with 2 from a list.
