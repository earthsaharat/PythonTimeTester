# PythonTimeTester

This is the runtime tester for your python program

## How to use

1. download this library
2. put TimeTester.py into same directory with your python file
3. import this library into your file

   ```python
   import TimeTester
   ```

4. put this code in your code

   ```python
   def x():
     # Put your program that you want to test here
     # Example
     print('Hello world')
   
   print(TimeTester.run(100000,x))
   ```

The number *100000* is how many running of your code that you want to test. 

The library will sum all of intervals for each running and return the average in milliseconds

*Saharat Saengsawang*
