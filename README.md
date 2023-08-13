# NumPy


NumPy Practices

* Importing Numpy library

* Creating arrays
* 




Creating an array between 1 and 7 with 20 equal points.
np.linspace(1,7,20)
array([1.        , 1.31578947, 1.63157895, 1.94736842, 2.26315789,
       2.57894737, 2.89473684, 3.21052632, 3.52631579, 3.84210526,
       4.15789474, 4.47368421, 4.78947368, 5.10526316, 5.42105263,
       5.73684211, 6.05263158, 6.36842105, 6.68421053, 7.        ])
np.linspace(1,7,20).reshape(5,4)
array([[1.        , 1.31578947, 1.63157895, 1.94736842],
       [2.26315789, 2.57894737, 2.89473684, 3.21052632],
       [3.52631579, 3.84210526, 4.15789474, 4.47368421],
       [4.78947368, 5.10526316, 5.42105263, 5.73684211],
       [6.05263158, 6.36842105, 6.68421053, 7.        ]])
Arrays indexing and slicing
arr = np.arange(1,26).reshape(5,5)
arr
array([[ 1,  2,  3,  4,  5],
       [ 6,  7,  8,  9, 10],
       [11, 12, 13, 14, 15],
       [16, 17, 18, 19, 20],
       [21, 22, 23, 24, 25]])
# selecting number 1 
arr [0,0]

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
