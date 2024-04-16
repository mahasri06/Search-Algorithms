# Aim:

To write a program to perform linear search and binary search using python programming.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
## Linear Search:
1.	Start from the leftmost element of array[] and compare k with each element of array[] one by one.
2.	If k matches with an element in array[] , return the index.
3.	If k doesn’t match with any of elements in array[], return -1 or element not found.
## Binary Search:
1.	Set two pointers low and high at the lowest and the highest positions respectively.
2.	Find the middle element mid of the array ie. arr[(low + high)/2]
3.	If x == mid, then return mid.Else, compare the element to be searched with m.
4.	If x > mid, compare x with the middle element of the elements on the right side of mid. This is done by setting low to low = mid + 1.
5.	Else, compare x with the middle element of the elements on the left side of mid. This is done by setting high to high = mid - 1.
6.	Repeat steps 2 to 5 until low meets high
## Program:
i)	#Use a linear search method to match the item in a list.
```
#Linear search and binary search
#Program developed by: Mahasri P
#registre number : 212223100029

def binary(array,k,low,high):
    while low<=high:
        mid = low +(high -low)//2
        if array[mid]== k:
            return mid
        elif array[mid] < k:
            low = low+1
        else:
            high =high -1
    return -1
array =eval(input())
array.sort()
k=int (input())

value =binary(array,k,0,len(array)-1)
if (value== -1):
    print(array)
    print("Element not found")
else:
    
    print(array)
    print("Element found at index: ",value)


```
ii)	# Find the element in a list using Binary Search(Iterative Method).
```
#Linear search and binary search
#Program developed by: Mahasri P
#registre number : 212223100029

def binary(array,k,low,high):
    while low<=high:
        mid = low +(high -low)//2
        if array[mid]== k:
            return mid
        elif array[mid] < k:
            low = low+1
        else:
            high =high -1
    return -1
array =eval(input())
array.sort()
k=int (input())

value =binary(array,k,0,len(array)-1)
if (value== -1):
    print(array)
    print("Element not found")
else:
    
    print(array)
    print("Element found at index: ",value)




```
iii)	# Find the element in a list using Binary Search (recursive Method).
```

#Linear search and binary search
#Program developed by: Mahasri P
#registre number : 212223100029

def binary(array,k,low,high):
    while low<=high:
        mid = low +(high -low)//2
        if array[mid]== k:
            return mid
        elif array[mid] < k:
            low = low+1
        else:
            high =high -1
    return -1
array =eval(input())
array.sort()
k=int (input())

value =binary(array,k,0,len(array)-1)
if (value== -1):
    print(array)
    print("Element not found")
else:
    
    print(array)
    print("Element found at index: ",value)



```
## Sample Input and Output
i)	#Use a linear search method to match the item in a list.
![Screenshot 2024-04-16 082725](https://github.com/mahasri06/Search-Algorithms/assets/139841897/3bcab7e6-fbeb-4f2e-828e-2392a7b1af15)


ii)	# Find the element in a list using Binary Search(Iterative Method).
![Screenshot 2024-04-16 082233](https://github.com/mahasri06/Search-Algorithms/assets/139841897/f1f499aa-3fc7-4d6f-84d9-ff80a0ed3c70)

iii)	# Find the element in a list using Binary Search (recursive Method).

![Screenshot 2024-04-16 082541](https://github.com/mahasri06/Search-Algorithms/assets/139841897/81720193-59ce-4e5a-9359-4820a8d69e4e)



## Result
Thus the linear search and binary search algorithm is implemented using python programming.
