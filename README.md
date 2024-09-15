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




![image](https://github.com/user-attachments/assets/d3b9cec4-8992-4de7-95a1-f3e567971f14)


## OUTPUT:


![image](https://github.com/user-attachments/assets/75d06bd8-1e9e-43e2-beb1-566d48c2ec08)


