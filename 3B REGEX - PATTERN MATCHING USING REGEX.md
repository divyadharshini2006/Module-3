# Exp.No:3b  
## REGEX - PATTERN MATCHING USING REGEX

### AIM  
To Write a Python program that matches a string that begins with  "a"  followed by zero or more b's .

### ALGORITHM

1. Begin the program.
2. Use input() to get the string str from the user.
3. Define the regular expression pattern ^[a(b*)]+$.
4. Use re.search() to check if the string matches the pattern.
5. If a match is found, print "Found a match!". Otherwise, print "Not matched!".
6. Terminate the program.

### PROGRAM
```
import re
str=input()
pattern='^[a(b*)]+$'
x=re.search(pattern,str)
if x:
    print("Found a match!")
else:
    print("Not matched!")
```
### OUTPUT
![Screenshot 2025-04-27 153144](https://github.com/user-attachments/assets/e435e73e-cfe2-40c3-8aff-298c2ef06506)

### RESULT
Thus a Python program that matches a string that begins with  "a"  followed by zero or more b's has been successfully implemented.
