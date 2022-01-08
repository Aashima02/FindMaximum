# Find the maximum of a list of numbers
## AIM:
To write a program to find the maximum of a list of numbers.

## EQUIPMENT'S REQUIRED:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner

## ALGORITHM:
1.	Get the list of marks as input
2.	Use the sort() function or max() function or use the for loop to find the maximum mark.
3.	Return the maximum value

## PROGRAM:

i)	# To find the maximum of marks using the list method sort.
```
Program to mark the maximum of marks using the list method sort
Developed by: Aashima Nazreen Sayeed S
RegisterNumber: 21500368

def max_marks(marks):
    marks.sort()
    max_mark=marks[-1]
    return max_mark
```
ii)	# To find the maximum marks using the list method max().
```
Program to find the maximum marks using the list method max().
Developed by: Aashima Nazreen Sayeed S
RegisterNumber: 21500368

def max_marks(marks):
    max_mark=max(marks)
    return max_mark
```

iii) # To find the maximum marks without using builtin functions.
```
Program to the maximum marks without using builtin functions.
Developed by: Aashima Nazreen Sayeed S
RegisterNumber: 21500368

def max_marks(list1):
    max_mark=0
    for i in list1:
        if i>max_mark:
            max_mark=i
    return max_mark
```
## SAMPLE INPUT AND OUTPUT:

### INPUT:
![input](./img/max_marks1.jpg) 

### OUTPUT:
![output1](https://user-images.githubusercontent.com/93427086/148647982-9e0c9ebb-1348-4dde-accd-7842ed108e48.png)
![output2](https://user-images.githubusercontent.com/93427086/148647985-de759bdc-d1f6-44a8-9221-6e88e4757372.png)
![output3](https://user-images.githubusercontent.com/93427086/148647989-5adb6160-57d5-40be-9e13-3df46fe84deb.png)


## RESULT:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
