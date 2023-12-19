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
Developed by:PREM KUMAR G
RegisterNumber:23003614
def max_marks(marks):
      marks.sort()
      large=marks[-1]
      return large
```

ii)	# To find the maximum marks using the list method max().
```Python
Developed by:PREM KUMAR G
RegisterNumber:23003614
def max_marks(marks):
    max1=max(marks)
    return max1
```

iii) # To find the maximum marks without using builtin functions.
```Python
Developed by:PREM KUMAR G
RegisterNumber:23003614
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max
```
## Output:
Maximum of marks using the list method sort
![Screenshot 2023-11-28 140358](https://github.com/PremkumarG3/FindMaximum/assets/138955646/f0b3afd3-7719-4098-98ba-d7aded200aa8)
maximum marks using the list method max()
![Screenshot 2023-11-28 140412](https://github.com/PremkumarG3/FindMaximum/assets/138955646/952165ea-7b6d-4abd-b850-3a0ea96b7ebc)
 maximum marks without using builtin functions
![Screenshot 2023-11-28 140423](https://github.com/PremkumarG3/FindMaximum/assets/138955646/8881a236-f8a0-42f4-80ce-997eeb63d9f7)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
