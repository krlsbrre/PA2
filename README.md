# Programming Assignment #2

## Description
This repository contains two Python-based data analytics problems:

1. **Normalization Problem**: Creating a random 5x5 array, normalizing it by subtracting the mean and dividing by the standard deviation, and saving the result.
2. **Divisible by 3 Problem**: Creating a 10x10 array containing squares of the first 100 integers, finding all elements divisible by 3, and saving the result.

## Problem Breakdown
### 1. Normalization Problem:
Normalization is one of the most basic preprocessing techniques in
data analytics. This involves centering and scaling process. Centering means subtracting the data from the
mean and scaling means dividing with its standard deviation. Mathematically, normalization can be
expressed as: 
![image](https://github.com/user-attachments/assets/568b7fa6-848c-4c6c-a467-3eb869cbbfb1)

In Python, element-wise mean and element-wise standard deviation can be obtained by using .mean() and
.std() calls.
In this problem, create a random 5 x 5 ndarray and store it to variable X. Normalize X. Save your normalized
ndarray as X_normalized.npy

#### Expected output:
![image](https://github.com/user-attachments/assets/1e13869f-4686-4466-b38e-cea90629f75d)

### 2. Divisible by 3 Problem
#### Create the following 10 x 10 ndarray
![image](https://github.com/user-attachments/assets/f193f90e-8bca-4082-8145-de196075e6f0)

which are the squares of the first 100 positive integers.
From this ndarray, determine all the elements that are divisible by 3. Save the result as div_by_3.npy

#### Expected output:
![image](https://github.com/user-attachments/assets/2f6a227a-434e-479b-875f-2c1d711b364d)

## Getting Started

### Prerequisites
You need Python and `numpy` installed. To install `numpy`, run:

```bash
pip install numpy
```

## Running the code

#### 1. Clone the repository:
```bash
git clone https://github.com/krlsbrre/PA2.git
```
#### 2. Navigate to the project directory and drag & upload the .ipynb file to Jupyter Notebook


## Author

- [@krlsbrre - Karlos Louis M. Sabarre - 2ECE-A](https://www.github.com/krlsbrre)
