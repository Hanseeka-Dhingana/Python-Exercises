# Introduction to Data Handling
## Basic Questions   
### Data Types in Python
1. What will be the output of the following code?   
``` python
a = 10
print(type(a))
``` 
2. Explain the difference between mutable and immutable data types with examples.     
3. How can you represent an integer in binary, octal, and hexadecimal formats? Provide examples.   
4. What is the purpose of the type() function in Python?
5. Differentiate between int, float, and complex numeric data types in Python.   
6. Explain the concept of sequences in Python and give examples of sequence data types.   
7. Discuss the use of sets in Python and provide examples.
8. Explain the concept of type casting in Python.
9. What is the difference between a shallow copy and a deep copy in Python dictionaries?
10. What is the purpose of the None data type in Python?
11. What is a literal in Python?
12. What are the different types of literals in Python with examples?
13. What is the difference between a single-quoted string and a triple-quoted string?
14. How do you define a complex number in Python? Provide an example.
15. What is difference between static typing dynamic typing in Python? Does Python support static typing natively?
16. How does Python handle variable types at runtime?

<br>   

### Type Conversion in Python
1. What is type conversion in Python?   
2. What is the difference between implicit and explicit type conversion?  
3. Name five built-in functions used for type conversion in Python.  
4. What happens when you try to convert a complex number to an integer?  
5. What is the output of int(True) and int(False)?  
6. Can a string containing decimal values (e.g., "10.5") be converted using int()? Why or why not?
7. What is the output of bool(0), bool(10), and bool("")? Explain.
8. How do you convert a float to a string in Python? Provide an example.
9. What is the output of complex(5, -3)?

<br>  

### Constants in Python

1.What are constants in Python, and how do they differ from regular variables?  
2. Why does Python not have built-in support for constants like some other programming languages?    
3. What naming conventions should be followed when defining constants in Python? Explain with examples.  
4. How does using uppercase letters for constants improve code readability and maintainability?   
5. Why should constants be defined at the top of a Python module or script?   
6. Explain the concept of immutability in the context of constants. How can developers enforce immutability in Python?    
7. How can constants help in avoiding the use of magic numbers in a Python program? Give an example.   
8. What are the advantages of using named constants instead of hard-coded values in a program?     
9. Why is it a best practice to add comments or docstrings to constants? Provide an example.    
10. What are the benefits of using a separate module for constants in larger projects?    
11. If Python does not enforce constant behavior, how can developers prevent accidental modification of constants?    
12. Describe a scenario where not using constants could lead to errors or confusion in a project.    
13. Can constants be defined inside functions in Python? If yes, explain with an example.   
14. What are some common use cases where constants are essential in Python programs?     
15. Explain how constants improve collaboration in a team-based development environment.    
16. How does defining constants help in debugging and modifying a program?     
17. In what situations might a developer choose to use constants instead of variables?    
18.  How does using constants help in adapting a program to future changes more efficiently?        

<br>

### Introduction to Python Collection/Data Structures  
1. What are Python collections, and why are they important in programming?    
2. Explain the differences between mutable and immutable collections in Python.   
3. Describe the key differences between ordered and unordered collections in Python.    
4. What is a list in Python? How is it different from other collection types?   
5. What is list comprehension? How does it improve efficiency in Python?   
6. What is a tuple in Python? How does it differ from a list?   
7. Why are tuples considered immutable, and what are the advantages of immutability?   
8. Explain the concept of tuple unpacking with an example.   
9. How do sets handle duplicate elements in Python?   
10. What are the key advantages of using sets in Python?   
11. What is a frozenset in Python, and how is it different from a regular set?    
12. In what scenarios would using a frozenset be more beneficial than a normal set?    
13. What is a dictionary in Python, and how does it store data?   
14. What is the purpose of mapping types in Python, and how are they used?    
15. How can specialized mapping types improve data organization in Python?   

<br>

### Working with Date and Time

1. Explain the importance of working with date and time in Python.   
2. What are the different modules available in Python for handling date and time?     
3. How can you retrieve the current date and time using the datetime module?    
4. What is the difference between datetime.now() and datetime.utcnow()?
5. How can you combine separate date and time objects into a single datetime object?
6. Differentiate between the date class and the time class in the datetime module.
7. What are the functions strftime() and strptime() used for?   
8. List and explain any five commonly used date/time format codes.  
9. How can you calculate the difference between two dates using timedelta?
10. How can you compare two datetime objects in Python?
11. How can you sort a list of datetime objects in ascending order?
12. Explain the use of the time.sleep() function with an example.
13. Mention two practical use cases of introducing execution delays in a program.
14. How can you calculate the execution time of a program using time.time()?
15. What is the difference between time.time() and time.perf_counter()?

<br>  

## Exercise
### Data Types in Python
1. Write a Python program to take a binary number as input and convert it to decimal, octal, and hexadecimal.    
2. Write a Python program to check if a given number is a palindrome in binary form.   
3. Write a Python program to convert a floating-point number to its scientific notation.   
4. Write a Python program to check if a given floating-point number is an integer (e.g., 5.0 is an integer).    
5. Write a Python program to multiply two complex numbers and display the result.    
6. Write a Python program to check if a string is a palindrome.   
7. Write a Python program to split a string into a list of words and then join them back into a single string with spaces in between.     
8. Write a Python program to format a string using f-strings, where you include variables for name, age, and salary.        
9. Write a Python program to print a string that includes a newline character (\n) and a tab character (\t).    
10. Write a Python program to create a list of integers and perform basic operations like appending, removing, and sorting.    
11. Write a Python program to concatenate two tuples and create a new tuple.   
12. Write a Python program to create a set of integers and perform operations like union, intersection, and difference.    
13. Write a Python program to remove duplicates from a list using a set.   
14. Write a Python program to iterate through a dictionary and print all key-value pairs.    
15.  Write a Python program to create a function that returns None and explain its use case.

<br>  

### Type Conversion in Python   
1. Write a Python program to convert a string containing a number (e.g., "123") to an integer and a float. Handle invalid inputs gracefully (e.g., "abc").
```  
Input Example: "123", "45.67", "abc"
Output Example: 123, 45.67, Invalid input
```
2.  Write a Python program to create a complex number with a real part as an integer and an imaginary part as a float. Convert it to a string and print the result.
```
Input Example: 5, 2.5
Output Example: "(5+2.5j)"  
```    

 3. Write a Python program to convert the following values to boolean using the bool() function: `0`, `1`,` 0.0`, `10.5`, `""`, `"Hello"`. Print the results. 
```
Output Example: False, True, False, True, False, True  
```

4. Addition of string and integer Using Explicit Conversion.  
``` python
       num_string = '12'
       num_integer = 23
```
```
Output: sum: 35
```
5. Write a Python program to convert a string to a float. Handle the ValueError exception if the string cannot be converted to a float.

```
Input Example: "45.67", "abc"
Output Example: 45.67, Invalid input
```   

6. Write a Python program to convert a binary string (e.g., "1010") to an integer without using the int() function. Print the result.

7. Write a Python program to convert a list of integers to a list of floats and a list of booleans. Print the results.   
``` 
Input Example: [0, 1, 2, 3]
Output Example: [0.0, 1.0, 2.0, 3.0], [False, True, True, True]
``` 

8. Write a Python program to calculate the area of a circle. Take the radius as input (as a string) and convert it to a float. Handle invalid inputs gracefully.

```
Input Example: "5.5", "abc"
Output Example: Area: 95.033, Invalid input
```

<br> 

### Constants in Python  
1. Write a Python program to calculate the gravitational force between two objects using the formula:          
                   <h4 style="text-align:center;">$$F=  {G⋅m1⋅m2 \over  r^2 }$$ </h4>             
use the gravitational constant `G = 6.674 x 10^-11` and r as input and print the force.
2. Write a Python program to calculate the area of a rectangle. Replace the magic numbers for length and width with constants `LENGTH` and `WIDTH.` Print the area.
3. Write a Python program to calculate the kinetic energy of an object using the formula:     
                   <h4 style="text-align:center;">$$KE = { {1\over2}.m . v^2 }$$ </h4>  
Store the constant 1/2 in a module named constants.py and import it into your program. Take mass (m) and velocity (v) as input and print the kinetic energy.
4. Write a Python program to calculate the body mass index `(BMI)` using the formula:      
                   <h4 style="text-align:center;">$$BMI = {weight \over height^2}$$ </h4>  
Use constants for the conversion factor from pounds to kilograms `(POUNDS_TO_KG = 0.453592)` and from inches to meters `(INCHES_TO_METERS = 0.0254)`. Take weight in pounds and height in inches as input and print the BMI.

<br>   

### Special Data Types
1. Write a Python function that takes a number as input and returns None if the number is negative. Otherwise, return the square of the number. Test the function with both positive and negative inputs.
``` 
Input Example: 5, -5
Output Example: 25, None
```
2. Write a Python program to manage a to-do list. Use None as a placeholder for incomplete tasks. Print the to-do list, replacing None with "Incomplete" for display purposes.
```
Input Example: ["Task 1", None, "Task 3"]
Output Example: ["Task 1", "Incomplete", "Task 3"]
```

3. Write a Python program to validate user input. If the user enters an empty string, return None. Otherwise, return the input in uppercase.

4. Write a Python program to simulate a student grading system. Use None to represent missing grades. Calculate the average grade, ignoring None values.
```
Input Example: [85, None, 90, 75, None]
Output Example: Average grade: 83.33
```
5. Write a Python program to handle a function that may return None. If the function returns None, print "No result found." Otherwise, print the result.

<br>   

### Introduction to Python Collection/Data Structures  

1. Write a Python program to create a list of integers, add a new element to the list, and then remove the second element. Print the final list.   
2. Write a Python program to find the sum of all elements in a list using a loop. Print the sum.   
3. Write a Python program to create a tuple of mixed data types (e.g., integers, strings, floats) and print each element along with its data type.   
4. Write a Python program to unpack a tuple into individual variables and print them.   
5. Write a Python program to create two sets and perform the following operations: union, intersection, and difference. Print the results.
```
Input Example: {1, 2, 3}, {3, 4, 5}
Output Example: Union: {1, 2, 3, 4, 5}, Intersection: {3}, Difference: {1, 2}
```                       
6. Write a Python program to check if a set is a subset of another set. Print the result.
```
Input Example: {1, 2}, {1, 2, 3, 4}
Output Example: True
```    
7. Write a Python program to create a frozenset and demonstrate that it is immutable by trying to add or remove elements. Handle the error gracefully.
```
Input Example: [1, 2, 3]
Output Example: Frozenset: frozenset({1, 2, 3}), Error: Cannot modify frozenset
```   
8. Write a Python program to create a dictionary with keys as names and values as ages. Add a new key-value pair and then delete an existing key-value pair. Print the final dictionary.   
9. Write a Python program to iterate through a dictionary and print all key-value pairs.
10. Write a Python program to merge two dictionaries into one. Print the merged dictionary.
11. Write a Python program to count the frequency of each character in a string using defaultdict. Print the character frequencies.
```
Input Example: "hello"
Output Example: {'h': 1, 'e': 1, 'l': 2, 'o': 1}
```
12. Write a Python program to group a list of words by their first letter using defaultdict. Print the grouped words.
```
Input Example: ["apple", "banana", "cherry", "apricot", "blueberry"]

Output Example: {'a': ['apple', 'apricot'], 'b': ['banana', 'blueberry'], 'c': ['cherry']}
``` 

13. Write a Python program to create a nested dictionary to store student information (e.g., name, age, grades). Print the nested dictionary.
```
Input Example: {"Alice": {"age": 25, "grades": [90, 85, 88]}}

Output Example: {"Alice": {"age": 25, "grades": [90, 85, 88]}}
```

<br>  

### Working with Date and Time   
1. Write a Python program to get the current date and time using the datetime module. Print the result in the format: YYYY-MM-DD HH:MM:SS.   
2. Write a Python program to combine a given date (2025-01-29) and time (15:45:00) into a single datetime object. Print the combined datetime.  
3. Convert string datetime into a datetime object.   
4. Subtract a week (7 days)  from a given date in Python.
5. Write a Python program to convert a datetime object to a string in the format Month DD, YYYY. For example: January 29, 2025.   
6. Write a Python program to add 5 seconds to the current time.  
7. Write a Python program to select all the Sundays in a specified year.   
8. Write a Python program to get days between two dates.  
9. Write a Python program to test the third Tuesday of a month.  
10. Write a Python program to get the last day of a specified year and month.  
11. Write a Python program to print a string five times, with a delay of three seconds.  
12. Write a Python program to add 5 days to the current date and print the new date.  
13. Write a Python program to compare two dates (2025-01-01 and 2025-01-29) and print which date is earlier.  
    ```
      Output Example: 2025-01-01 is earlier than 2025-01-29
    ```
14. Write a Python program to find the minimum and maximum dates from a list of dates: `[2025-01-01, 2024-12-31, 2025-02-01].`  
15. Write a Python program to check if a given year is a leap year using the calendar module.  
16.  Write a Python program to sort a list of dates in ascending order: [2025-01-01, 2024-12-31, 2025-02-01]. Print the sorted list.   
17. Write a Python program to calculate the time taken to sort a list of 10,000 random numbers. Print the execution time in milliseconds.  
18. Write a Python program to display the calendar for January 2025 using the calendar module.  
19. Write a Python program to calculate the number of days between your birthdate and today. Print the result.  
    ```
    Input Example: 1990-05-15
    Output Example: Number of days since birth: 12,345
    ```  
20. Write a Python program to calculate the age of a person in years, months, and days given their birthdate (1990-05-15). Print the result.
```
Output Example: Age: 34 years, 8 months, 14 days
```




 
