# EX 3a: Find the maximum of a list of numbers
## Date: 05.09.23
## Aim:
To write a program to find the maximum of a list of numbers.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1.	Get the list of marks as input
2.	Use the sort() function or max() function or use the for loop to find the maximum mark.
3.	Return the maximum value
## Program:

i) To find the maximum of marks using the list method sort.
``` 
Program to mark the maximum of marks using the list method sort
Developed by: DIVYA.A
RegisterNumber: 212222230034

def max_marks(marks):
    marks.sort()
    max=marks[-1]
    return max
```

ii) To find the maximum marks using the list method max().
```
Program to find the maximum marks using the list method max().
Developed by: DIVYA.A
RegisterNumber: 212222230034

def max_marks(marks):
    max_marks=max(marks)
    return max_marks
```

iii) To find the maximum marks without using builtin functions.
```
Program to the maximum marks without using builtin functions.
Developed by: DIVYA.A
RegisterNumber: 212222230034

def max_marks(list1):
   max=list1[0]
   for i in list1:
       if i>max:
           max=i
   return max       
```

## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
i) To find the maximum of marks using the list method sort.
![Exp 3a(1)](https://github.com/Divya110205/FindMaximum/assets/119404855/28240ab7-652b-439d-857d-c1e98d5a97ba)

ii) To find the maximum marks using the list method max().
![Exp 3a(2)](https://github.com/Divya110205/FindMaximum/assets/119404855/a70cd6fe-7749-4f22-b6f6-f0780aeb2b63)

iii) To find the maximum marks without using builtin functions.
![Exp 3a(3)](https://github.com/Divya110205/FindMaximum/assets/119404855/0fd47b8c-e457-4d6e-810f-4b97113f3c5c)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
