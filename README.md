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
```Python
  #Write your code here
def max_marks(marks):
  a=max(marks)
  return a
```

ii)	# To find the maximum marks using the list method max().
```Python

def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large
```

iii) # To find the maximum marks without using builtin functions.
```Python
def max_marks(list1):
    # write your code heredef max_marks(list1):
    max_mark=0
    for i in list1:
        if i>max_mark:
            max_mark=i
    return max_mark
```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
![output](https://github.com/Nagadurg/FindMaximum/blob/3e269833519d2a3db9d8417507dc88ccdc3acfa4/output1.PNG)
![output](https://github.com/Nagadurg/FindMaximum/blob/3e269833519d2a3db9d8417507dc88ccdc3acfa4/output2.PNG)
![output](https://github.com/Nagadurg/FindMaximum/blob/3e269833519d2a3db9d8417507dc88ccdc3acfa4/output3.PNG)
## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
