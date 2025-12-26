# NumPy Program: Column-wise Sorting of a 2D Array

## 🎯 Aim
To write a **NumPy** program that sorts the elements in each column of a given 2D array in ascending order.

## 🧠 Algorithm

1. **Import NumPy**: Start by importing the NumPy library.
2. **Get Input**: Accept a 2D NumPy array from the user.
3. **Sort Column-wise**: Use the `np.sort()` function with `axis=0` to sort each column in ascending order.
4. **Store Result**: Store the sorted result in a new array.
5. **Display Output**: Print the original array and the column-wise sorted array.

## 🧾 Program
~~~
import numpy as np
n,m=map(int,input().split())
ar=np.array([list(map(int,input().split()))for i in range(n)])
c=np.sum(ar,axis=0)
r=np.prod(c)
print(r)
~~~

## Output
<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/ab8624ae-fcdf-42c7-8e03-7054a0a096bd" />

## Result
Thus, the program has been executed successfully.
