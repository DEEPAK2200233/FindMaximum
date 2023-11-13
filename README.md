# Find the maximum of a list of numbers
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

i)	# To find the maximum of marks using the list method sort.
``` 
Program to mark the maximum of marks using the list method sort
Developed by: DEEPAK RAJ S
RegisterNumber: 212222240023

def max_marks(marks):
    marks.sort()
    max=marks[-1]
    return max
```

ii)	# To find the maximum marks using the list method max().
```
Program to mark the maximum of marks using the list method max()
Developed by: DEEPAK RAJ S
RegisterNumber: 212222240023

def max_marks(marks):
    max_value=max(marks)
    return max_value
```
iii) # To find the maximum marks without using builtin functions.
``` 
Program to mark the maximum of marks using builtin functions.
Developed by: DEEPAK RAJ S
RegisterNumber: 212222240023

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

To find the maximum of marks using the list method sort.

![image](https://github.com/DEEPAK2200233/FindMaximum/assets/118707676/b2bd19a3-9257-437f-9746-614ed73ef16a)

To find the maximum marks using the list method max().

![image](https://github.com/DEEPAK2200233/FindMaximum/assets/118707676/66b29e94-2815-42ca-837c-76a2cbfe3844)

To find the maximum marks without using builtin functions.

![image](https://github.com/DEEPAK2200233/FindMaximum/assets/118707676/839c2828-1de0-41f1-ba2f-05d146dd6b3f)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
