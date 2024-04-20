# Python Learning Guide
Welcome back to the Python Beginners Guide Part 2! 🙌
This README will expand your Python knowledge by introducing more concepts and control structures that will help you become a proficient Python programmer. This README will expand your Python knowledge by introducing more concepts and control structures that will help you become a proficient Python programmer.

Here, we'll also explore Python, diving deep into the world of NumPy and Pandas. This space is designed to be your guide, offering insights, tips, and practical examples for harnessing the power of Python in data manipulation and analysis. Whether you're just starting out or a seasoned coder, join us on this exciting journey through the world of Python, NumPy, and Pandas!

## Function
---
A function is a block of code that performs a specific task. It allows you to organize your code into reusable components, making it easier to manage and maintain. Functions can take input parameters, perform operations, and return output values.

#### ***1. Definition***
Define a function using the def keyword followed by the function name and parentheses containing any input parameter
![image](https://github.com/inialif/PythonLearning2/assets/165395693/2103f935-02ba-4956-b5bd-cd06acb52a19)
		   

#### ***2. Call***
Call a function by using the function name followed by parentheses. You can pass arguments to the function if it requires input parameters.
      ![image](https://github.com/inialif/PythonLearning2/assets/165395693/b9a956cd-a09e-48fb-9ca7-a4e03116f00d)

#### ***3. Return***
Use the return statement to return a value from a function. The function will terminate and return the specified value.
![image](https://github.com/inialif/PythonLearning2/assets/165395693/3e936aad-470c-4125-ae9c-025add9d7f16)

#### ***4. Pass by Reference vs Value***
- In Python, arguments are passed by reference, meaning the function receives a reference to the object in memory. Changes made to mutable objects (e.g., lists) within the function will affect the original object.

- Unlike mutable objects, immutable objects (e.g., integers, strings) cannot be modified in place. If you reassign an immutable object within a function, it will create a new object in memory.

![image](https://github.com/inialif/PythonLearning2/assets/165395693/23cdcda5-118d-4794-9fdb-f6255fb659cf)


## NumPy
---
- NumPy is a powerful library for numerical computing in Python. It provides support for multidimensional arrays, mathematical functions, and linear algebra operations. NumPy is widely used in data analysis, machine learning, and scientific computing.
- To use NumPy, you need to import the library using the import numpy as np statement.
  
#### NumPy Array
A NumPy array is a grid of values with the same data type. It can be created using the np.array() function by passing a list or tuple of values.
![image](https://github.com/inialif/PythonLearning2/assets/165395693/f67db605-694c-4029-ae07-6837553847ac)


#### Dimension in Arrays
- Dimensions in NumPy arrays refer to the number of axes or dimensions in the array. A 1D array has one axis, a 2D array has two axes, and so on. Uses ndim attribute to get the number of dimensions.
  ![image](https://github.com/inialif/PythonLearning2/assets/165395693/a0438b0b-25c0-4479-9b02-20c7e3dce162)

- Customizing the number of dimensions in a NumPy array using the ndmin parameter.
  ![image](https://github.com/inialif/PythonLearning2/assets/165395693/bcd44221-dfcf-4f94-b0b1-c9a08010d28b)

#### Get a Element From Array
- Use indexing to access elements in a NumPy array. You can specify the row and column indices to retrieve a specific element.
  ![image](https://github.com/inialif/PythonLearning2/assets/165395693/4af1cbda-0f10-4734-b2ed-ed4569df28c3)

- Get Element from Dimensional Array.


   ![image](https://github.com/inialif/PythonLearning2/assets/165395693/daaf474f-c57d-481b-a0a6-b71cc1fb15c7)

## Pandas
---
- Pandas is a popular data manipulation library built on top of NumPy. It provides data structures like Series and DataFrame, which are essential for working with structured data.
- To use Pandas, you need to import the library using the import pandas as pd statement.

### Pandas - Series
A Pandas Series is a one-dimensional labeled array capable of holding data of any type. It is similar to a NumPy array but with additional indexing capabilities. pd.Series() function is used to create a Series.

![image](https://github.com/inialif/PythonLearning2/assets/165395693/dde95eaa-e987-402d-b94d-4f6d3fda3695)

#### 1. Implicit and Explicit Indexing
By default, a Series is created with an implicit integer index starting from 0. You can specify custom labels for the index using the index parameter.
  - Explicit Indexing : Allows you to assign custom labels to the elements in a Series. You can use the index parameter to specify the index labels.
    ![image](https://github.com/inialif/PythonLearning2/assets/165395693/7f9a7f5c-e4b6-405b-b700-aaf86ce90a6c)

  - Implisit Indexing : Uses the default integer index to access elements in a Series. You can use the default index to retrieve values from the Series.
    ![image](https://github.com/inialif/PythonLearning2/assets/165395693/35690fda-e720-439c-98c8-6a1bf58dc0e7)

#### 2. Data Slicing
Data slicing allows you to extract a subset of data from a Series based on the index labels or positions. You can use slicing to select specific elements or ranges of elements.
- Explicit Indexing

  ![image](https://github.com/inialif/PythonLearning2/assets/165395693/bdd7ac69-9691-4e58-a601-fdb5b94aeee4)
- Implisit Indexing

   ![image](https://github.com/inialif/PythonLearning2/assets/165395693/4f7a1d48-5742-400c-9d81-535f8ca63fc3)

#### 3. Loc and Iloc
The loc attribute is used to access data based on explicit index labels, while 
the iloc attribute is used to access data based on implicit integer positions.
- Loc

  ![image](https://github.com/inialif/PythonLearning2/assets/165395693/e4c9a047-69f8-4489-bff6-be5bf526d35d)

- Iloc

  ![image](https://github.com/inialif/PythonLearning2/assets/165395693/d20bdb60-6beb-4aa9-a52a-96adc37a8ca4)

#### 4. Dictionary Series
You can convert a Python dictionary into a Pandas Series using the pd.Series() function. The keys of the dictionary become the index labels, and the values become the data elements.
- Data Dictionary

  ![image](https://github.com/inialif/PythonLearning2/assets/165395693/d1b03614-3894-4d88-8a12-25b6067b9ecd)
  ![image](https://github.com/inialif/PythonLearning2/assets/165395693/59413c8b-f56b-49dd-a7a0-55f0af156d5c)

- Data Series

  ![image](https://github.com/inialif/PythonLearning2/assets/165395693/a98ee9ab-a9bf-45e6-8a4f-7bf664a25a2b)
  ![image](https://github.com/inialif/PythonLearning2/assets/165395693/16776761-6b18-4021-9267-3958341c3ab8)

### Pandas - DataFrame
A Pandas DataFrame is a two-dimensional labeled data structure with columns of potentially different types. It is similar to a spreadsheet or SQL table and is widely used for data analysis and manipulation.

#### 1. Convert Data Series to DataFrame
You can convert a Pandas Series into a DataFrame using the pd.DataFrame() function. The Series elements become the data values in the DataFrame, and the index labels become the row labels.
DataFrame : 

![image](https://github.com/inialif/PythonLearning2/assets/165395693/a9be3287-61ac-46b6-a80e-c9add6ba2860)

#### 2. Accessing Data in DataFrame
You can access data in a DataFrame using the column names. Use the column name as an index to retrieve the values in that column.

![image](https://github.com/inialif/PythonLearning2/assets/165395693/d3f6c436-ae67-42c2-a71e-c66f708b0d8a)

#### 3. Load Data from CSV File
- You can load data from a CSV file into a Pandas DataFrame using the pd.read_csv() function. Specify the file path as an argument to read the CSV file and create a DataFrame.
- Data CSV Source :

  ![image](https://github.com/inialif/PythonLearning2/assets/165395693/d88f7a3e-ff93-44b0-bcb6-c2a89537c120)

  - head()
     + The head() method is used to display the first few rows of a DataFrame. By default, it shows the first five rows, but you can specify the number of rows to display.
       
       ![image](https://github.com/inialif/PythonLearning2/assets/165395693/d2f62fa8-2c3d-4607-b200-1e047e09cac8)

  - info()
    + The info() method provides a concise summary of the DataFrame, including the data types, non-null values, and memory usage. It is useful for understanding the structure of the DataFrame.
      
      ![image](https://github.com/inialif/PythonLearning2/assets/165395693/19f0ed37-c5f3-4305-8d20-268385474f28)

  - notnull()
    + he notnull() method returns a boolean mask indicating whether each value in the DataFrame is not null (i.e., contains a valid value). It is useful for filtering out missing data.
      
      ![image](https://github.com/inialif/PythonLearning2/assets/165395693/257ce972-1d0d-4f1b-9a3d-7823ab36d14c)

    + notnull().sum() used to count the number of non-null values in each column.
      
      ![image](https://github.com/inialif/PythonLearning2/assets/165395693/84457bf9-f003-4a71-b972-3a546c9b28af)

  - isnull()
    + The isnull() method returns a boolean mask indicating whether each value in the DataFrame is null (i.e., missing or NaN). It is useful for identifying missing data in the DataFrame.
      
      ![image](https://github.com/inialif/PythonLearning2/assets/165395693/4678de63-199b-4ec5-be32-dcf6f9b7211c)

    + isnull().sum() used to count the number of missing values in each column.
      
      ![image](https://github.com/inialif/PythonLearning2/assets/165395693/ed658773-6ba7-40f8-8f49-242fdaad045d)

  - tail()
    + The tail() method is used to display the last few rows of a DataFrame. By default, it shows the last five rows, but you can specify the number of rows to display.
      
      ![image](https://github.com/inialif/PythonLearning2/assets/165395693/128961ab-c1f9-4c46-a8f4-5388b8749a15)

  - shape
    + The shape attribute returns a tuple representing the dimensions of the DataFrame (number of rows, number of columns). It is useful for understanding the size of the DataFrame.
      
      ![image](https://github.com/inialif/PythonLearning2/assets/165395693/54bd95c6-bc94-4808-8ef8-e8f0957eb9c0)

  - columns
    + he columns attribute returns the column labels of the DataFrame. It is useful for accessing and manipulating the column names.
      
      ![image](https://github.com/inialif/PythonLearning2/assets/165395693/317d48a3-a311-473b-90c2-0aed8d973529)

  - index
    + The index attribute returns the row labels of the DataFrame. It is useful for accessing and manipulating the row indices.
      
      ![image](https://github.com/inialif/PythonLearning2/assets/165395693/e527643c-74b1-41a4-9223-c1acfe706ac3)

  - describe()
    + The describe() method generates descriptive statistics for the numerical columns in the DataFrame, including count, mean, standard deviation, minimum, maximum, and quartile values.
      
      ![image](https://github.com/inialif/PythonLearning2/assets/165395693/dd74b342-4149-476a-9c18-5dbfd6bfe034)

  - mean()
    + The mean() method calculates the mean value for each column in the DataFrame. It is useful for computing the average value of numerical data.
      
      ![image](https://github.com/inialif/PythonLearning2/assets/165395693/c1828ec8-11c8-44d6-9804-d3562bda0f47)

  - median()
    + The median() method calculates the median value for each column in the DataFrame. It is useful for finding the middle value of numerical data.
      
      ![image](https://github.com/inialif/PythonLearning2/assets/165395693/f26e2b37-c4f6-4091-bd96-57764ec76371)

  - mode()
    + The mode() method calculates the mode value for each column in the DataFrame. It is useful for finding the most frequently occurring value in categorical data.
      
      ![image](https://github.com/inialif/PythonLearning2/assets/165395693/d222dc8e-b8d4-46b5-a0e7-2d95871e1fd9)

  - max()
    + The max() method returns the maximum value for each column in the DataFrame. It is useful for finding the highest value in numerical data.
      
      ![image](https://github.com/inialif/PythonLearning2/assets/165395693/5cb5cd43-592e-4c62-97ca-348e85881b22)

  - min()
    + The min() method returns the minimum value for each column in the DataFrame. It is useful for finding the lowest value in numerical data.
      
      ![image](https://github.com/inialif/PythonLearning2/assets/165395693/728e4dec-bda5-49c9-a659-0565beff20bd)

  - unique()
    + The unique() method returns an array of unique values in a column of the DataFrame. It is useful for identifying distinct values in categorical data.
      
      ![image](https://github.com/inialif/PythonLearning2/assets/165395693/662057fa-580d-413f-a3bd-6a290c021bf9)

    + nunique() used to count the number of unique values in a column.
      
      ![image](https://github.com/inialif/PythonLearning2/assets/165395693/08cb9798-5e45-4aa2-825a-c0a9be35a1d3)

  - value_counts()
    + The value_counts() method returns the frequency of each unique value in a column of the DataFrame. It is useful for counting occurrences of different values.
      
      ![image](https://github.com/inialif/PythonLearning2/assets/165395693/94dc381f-3fb1-4792-b949-58b4d59bc769)

  - Get Specified Columns
    + You can select specific columns from a DataFrame by passing a list of column names inside square brackets. This allows you to focus on the columns of interest.
      
      ![image](https://github.com/inialif/PythonLearning2/assets/165395693/38127bac-de01-4731-a800-2d61e2322c2d)

    + You can filter data from columns based on specific conditions. Use the conditional statement inside square brackets to extract rows that meet the criteria.
      
      ![image](https://github.com/inialif/PythonLearning2/assets/165395693/5e7a6b51-8801-45ca-9fbd-a544354428a1)


## DateTime
---
+ The datetime module in Python provides classes for manipulating dates and times. It allows you to work with dates, times, and time intervals, making it easier to handle temporal data in your programs.
+ Example : Use strftime() method to format the date and time as a string. You can specify the format codes to customize the output.

  ![image](https://github.com/inialif/PythonLearning2/assets/165395693/e17d38ed-1f41-4f79-b056-f24fe0bc4b1f)

## Random Library
---
+ The random module in Python provides functions for generating random numbers. It is commonly used in simulations, games, and statistical applications where random values are required.
+ Example of Random Library :

  ![image](https://github.com/inialif/PythonLearning2/assets/165395693/e36b9d75-20e7-4eea-be1f-2b22002916fe)


## Text File - Open, Read, and Close
---
+ Reading and writing text files is a common task in Python programming. You can open a file, read its contents, and close the file once you're done. The open() function is used to open a file, and the read() method is used to read the file contents.
  - Open a File

    ![image](https://github.com/inialif/PythonLearning2/assets/165395693/ae0f5ca2-fec2-45b3-a490-789545afc43e)

  - Read File Contents
    
    ![image](https://github.com/inialif/PythonLearning2/assets/165395693/3640b1ac-8fc0-45d5-a421-be6b581a01df)

  - Close the File
    
    ![image](https://github.com/inialif/PythonLearning2/assets/165395693/6ac978b9-4309-4749-84a1-023c24d294f0)

# End Notes
---
As you conclude this part of our Python Mastery for Data Analysts guide, remember that Python is a versatile and powerful language extensively utilized across various fields, including data analysis, machine learning, and web development. By mastering foundational concepts like functions, NumPy, Pandas, datetime handling, the Random Library, and text file manipulation, you're equipping yourself with essential skills for real-world data analysis tasks.

This guide serves as a solid foundation for your Python journey, providing you with the necessary knowledge to continue building upon. Keep practicing, experimenting with different concepts, and working on projects to reinforce your understanding.

Keep up the great work, and may your learning journey be filled with success and discovery! 🚀
