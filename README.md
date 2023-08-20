# Assignment-1NumPy6_NumPy_Coding_Problems
1. Create a null vector of size 10 but the fifth value which is 1.
   import numpy as np

   vec=np.zeros(10)
   vec[4]=5
   print(vec)

2. Create a vector with values ranging from 10 to 49.
    import numpy as np

    vec = np.arange(10 , 50)
    print(vec)
   
4. Create a 3x3 matrix with values ranging from 0 to 8
    import numpy as np

    mat = np.arange(0 , 9).reshape((3 , 3))
    print(mat)
   
6. Find indices of non-zero elements from [1,2,0,0,4,0]
   import numpy as np

   arr = np.array([1,2,0,0,4,0])
   non_zero = np.nonzero(arr)
   print(non_zero)
   
7. Create a 10x10 array with random values and find the minimum and maximum values.
     import numpy as np

     arr = np.random.random((10 , 10))
     mini = arr.min()
     maxi = arr.max()
     print(arr)
     print("minimum number : ",mini)
     print("maximin number : ",maxi)
   
8. Create a random vector of size 30 and find the mean value.
   import numpy as np

   vec = np.random.random(30)
   mean = np.mean(vec)
   print(vec)
   print("mean value : ",mean)
