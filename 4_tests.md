# Writing tests

In the previous notebook you became familiar with the assert statement. 
Assert statements are a way of quickly checking if a certain snippet of code returns the expected output. 

Sometimes, you want to be able to quickly run a script to check if your code is working correctly. In such cases you will want to create some kind of test file that can test your code automatically. You have probably noticed that the PAs often have a subdirectory `tests` with some `.py` files with some tests in it. We will flip the switch now. We have provided you with a corrected and modified version of the function `max_even_squared` from last week. Now write a test for it!

## Task 1: Create a test in a py file
  
Create a test for `max_even_squared.py` in the provided file `my_test.py`

The first and second test is completed for you as an example.

It is up to you to write the rest of the tests.

The tests should:

- return an error when a list without any even numbers, such as `[1, 3, 5]`, are passed into the function
- return an error when when non-list objects, such as `'apple'`, are passed into the function
- return an error when lists with non-integer values, such as `[1, 3, 'apple']` are passed into the function
- return an error if an empty list is passed into the function

You can check what type of error occurs for each case by inspecting the original function and running the tests with `pytest my_test.py` in the terminal. To do so, please first install `pytest` with `conda install pytest` in your `mude-base` environment.

**Do not change any of the file names or add any additional test files of your own. This will cause the autograder to fail.**
