# PROGRAMMING ASSIGNMENT 2

NAME: PAOLO D. MENDOZA

SECTION: 2ECE-D

DATE: 5/09/2024

# DOCUMENTATION

# 1. NORMALIZATION PROBLEM: 
Normalization is one of the most basic preprocessing techniques in
data analytics. This involves centering and scaling process. Centering means subtracting the data from the
mean and scaling means dividing with its standard deviation.

### How I made this program:
1. Imported the numpy library which is ("import numpy as np")
2. Created a 5x5 array, generated using "np.random.random((5,5))". This creates a 5x5 matrix of random numbers between 0 and 1.
3. Normalizing the array : The array is normalized by first calculating the mean (X_mean = np.mean(random_array)) and the standard deviation (X_std = np.std(random_array)).
4. Then saving it to a file. This file is saved as .npy and is saved using np.save
5. Last, printing the array The saved array is then loaded back from the file using np.load


  ## CODE:




  
  ![image](https://github.com/user-attachments/assets/16431e34-42e5-4c0d-9011-e7aad281088f)

  ## OUTPUT:

The output is a 5x5 array of normalized values


  ![image](https://github.com/user-attachments/assets/589de54e-9698-44f3-92fa-d9a08c1697c0)



# 2. DIVISIBLE BY 3 PROBLEM: 
Create the following 10 x 10 ndarray.





![image](https://github.com/user-attachments/assets/d0c08bc9-9400-4598-ba19-16857eaa1eb1)

which are the squares of the first 100 positive integers.


## CODE:


1. Create a 10x10 ndarray (A) of the first 100 integers
.np.arange(1, 101) creates an array of numbers from 1 to 100.
.reshape((10, 10)) converts this 1D array into a 10x10 matrix.
2. Square each element of the array: "Squared_A = np.square(A)" This squares every element in the matrix A, resulting in a new matrix where each number is replaced by its square.
3. Filter elements divisible by 3: div_by_3 = "Squared_A[Squared_A % 3 == 0]"this selects all the elements from the squared matrix (Squared_A) that are divisible by 3 (% 3 == 0).
4. save the file to .npy
5. load the data using np.load
6. display data
 



![image](https://github.com/user-attachments/assets/d3b9cec4-8992-4de7-95a1-f3e567971f14)


## OUTPUT:

The output contains the squares of integers from 1 to 100 that are divisible by 3. These numbers are extracted from the squared 10x10 matrix and stored in a separate array. After saving and reloading, this array is displayed, showing only the squared values that meet the divisibility condition.



![image](https://github.com/user-attachments/assets/75d06bd8-1e9e-43e2-beb1-566d48c2ec08)


