# EXPERIMENT: 7
### NAME: AVINASH T
### REG NO: 212223230026
# Linear Search and Binary search
## Aim:
To write a program to perform linear search and binary search using python programming.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Linear Search:
1.	Start from the leftmost element of array[] and compare k with each element of array[] one by one.
2.	If k matches with an element in array[] , return the index.
3.	If k doesn’t match with any of elements in array[], return -1 or element not found.
### Binary Search:
1.	Set two pointers low and high at the lowest and the highest positions respectively.
2.	Find the middle element mid of the array ie. arr[(low + high)/2]
3.	If x == mid, then return mid.Else, compare the element to be searched with m.
4.	If x > mid, compare x with the middle element of the elements on the right side of mid. This is done by setting low to low = mid + 1.
5.	Else, compare x with the middle element of the elements on the left side of mid. This is done by setting high to high = mid - 1.
6.	Repeat steps 2 to 5 until low meets high
## Program:
i)	#Use a linear search method to match the item in a list.
```c
#DEVELOPED BY :AVINASH T
#REG NO:212223230026
#Use a linear search method to match the item in a list.
def binarySearchIter(lst, k, low, high):
    while low<=high:
        mid=low+(high-low)//2
        if lst[mid]==k:
            return mid
        elif lst[mid]<k:
            low=mid+1
        else:
            high=mid-1
    return -1
lst = eval(input())
lst.sort()
k = eval(input()) 
print(lst)
res=binarySearchIter(lst,k,0,len(lst)-1)
if res==-1:
    print("Element not found")
else:
    print("Element found at index: ",res)
```
ii)	# Find the element in a list using Binary Search(Iterative Method).
```c
#DEVELOPED BY :AVINASH T
#REG NO:212223230026
#Find the element in a list using Binary Search(Iterative Method).
def binarySearchIter(lst, k, low, high):
    while low<=high:
        mid=low+(high-low)//2
        if lst[mid]==k:
            return mid
        elif lst[mid]<k:
            low=mid+1
        else:
            high=mid-1
    return -1
lst= eval(input())
lst.sort()
k = eval(input()) 
print(lst)
res=binarySearchIter(lst,k,0,len(lst)-1)
if res==-1:
    print("Element not found")
else:
    print("Element found at index: ",res)
```
iii)	# Find the element in a list using Binary Search (recursive Method).
```c
#DEVELOPED BY :AVINASH T
#REG NO:212223230026
# Find the element in a list using Binary Search (recursive Method).
def binarySearchIter(lst, k, low, high):
    while low<=high:
        mid=low+(high-low)//2
        if lst[mid]==k:
            return mid
        elif lst[mid]<k:
            low=mid+1
        else:
            high=mid-1
    return -1
lst = eval(input())
lst.sort()
k = eval(input()) 
print(lst)
res=binarySearchIter(lst,k,0,len(lst)-1)
if res==-1:
    print("Element not found")
else:
    print("Element found at index: ",res)
```
## Input
i)	#Use a linear search method to match the item in a list.
![image](https://github.com/AVINASH05T/Search-Algorithms/assets/151514286/f2794e59-924a-4cf8-83ed-472cbdb846d4)
ii)	# Find the element in a list using Binary Search(Iterative Method).
![image](https://github.com/AVINASH05T/Search-Algorithms/assets/151514286/4755c72c-a87b-41c2-b1d0-0a8a4b0d6d64)
iii)	# Find the element in a list using Binary Search (recursive Method).
![image](https://github.com/AVINASH05T/Search-Algorithms/assets/151514286/704eb9a1-d038-436f-af47-c69de1a85204)

## Output:
i)	#Use a linear search method to match the item in a list.
![image](https://github.com/AVINASH05T/Search-Algorithms/assets/151514286/d277caf7-6b57-4b2e-a40a-8139d2e5bb2c)
ii)	# Find the element in a list using Binary Search(Iterative Method).
![image](https://github.com/AVINASH05T/Search-Algorithms/assets/151514286/e3221d9e-a9e1-4792-94bc-30eb6fcf18fa)
iii)	# Find the element in a list using Binary Search (recursive Method).
![image](https://github.com/AVINASH05T/Search-Algorithms/assets/151514286/3e0ee766-5563-4634-adb9-56a2fa16155d)

## Result
Thus the linear search and binary search algorithm is implemented using python programming.
