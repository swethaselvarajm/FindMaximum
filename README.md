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
```
#Developed by: SWETHA.S
#RegisterNumber: 212222230155
```
i)	# To find the maximum of marks using the list method sort.
```
def max_marks(marks):
    marks.sort()
    max=marks[-1]
    return max
```

ii)	# To find the maximum marks using the list method max().
```
def max_marks(marks):
    # write your code here
    max_marks=max(marks)
    return max_marks
```

iii) # To find the maximum marks without using builtin functions.
```
def max_marks(list1):
    # write your code here
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max    
```
## Sample Input:
![image](https://github.com/swethaselvarajm/FindMaximum/assets/119525603/0e880525-a5fc-4a0d-b9f0-6c07f545c76a)


## Output:
![image](https://github.com/swethaselvarajm/FindMaximum/assets/119525603/07bf74ec-bb64-4adc-801a-49edb83a004c)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
