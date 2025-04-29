# Exp.No:3c
## LIST - FINDING MAXIMUM VALUE FROM A LIST

---

### AIM  
To write a Python program to accept n numbers into a list and find the maximum value using built-in functions.

---

### ALGORITHM

1. Begin the program.
2. Accept an integer n from the user representing the number of elements in the list.
3. Initialize an empty list l.
4. Use a for loop to accept n integer inputs from the user and append them to the list.
5. After collecting all inputs, display the complete list.
6. Use the built-in max() function to find the largest number in the list.
7. Print the maximum value.
8. Terminate the program.

---

### PROGRAM
n=eval(input()) <br>
l=[]   <br>
for i in range (n):  <br>
    l.append(int(input()))  <br>
print("List =",l)  <br>
print("The maximum value is",max(l))  

### OUTPUT

![image](https://github.com/user-attachments/assets/26da6528-c598-4e58-ab57-de2d421c878b)


### RESULT
Thus the Python program to find the maximum value from a list using the max() function was executed successfully and the output was verified.
