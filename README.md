# NumPy


NumPy Practices

* Importing Numpy library

* Creating arrays
  
* Arrays indexing and slicing

* Arrays Operations

* 


# selecting number 12 
arr [2,1]

# selecting number 24 
arr [4,3]
24
# Select a range for the second and third rows with three middle columns only

arr[1:3,1:4]
array([[ 7,  8,  9],
       [12, 13, 14]])
# Select a range for the last two rows with the last column only

arr [3:,4:]
array([[20],
       [25]])
arr [1:4,2:5]
array([[ 8,  9, 10],
       [13, 14, 15],
       [18, 19, 20]])
Arrays Opersations
# sum of all values in arr

arr.sum()
325
# sum of values in certain column 

arr.sum(axis=0)
array([55, 60, 65, 70, 75])
