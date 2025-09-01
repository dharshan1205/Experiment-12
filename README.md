# Experiment-12
## Pytest Python program for Addition
# Aim:
To write a python program for addition of two numbers and test the test cases using Pytest.
# Algorithm: 
Step 1: Write the python program for addition of two numbers.

Step 2: Make sure that function name should be “def test_*():” and the line to be tested should have assert keyword at the beginning.

Step 3: Write some test cases for to be tested and save it as “test_add.py”.

Step 4: Open command prompt and change the directory to where pytest and program is saved and type “pytest test_add.py” and run it.

Step 5: Stop the program.
# Program:
```
def add(a,b): 
    return a+b 
def test_3_plus_5_equals_8(): 
    assert add(3,5) == 8 
def test_2_plus_3_equals_5(): 
    assert add(2,3) == 6
```
# Output
<img width="953" height="410" alt="image" src="https://github.com/user-attachments/assets/9614498f-1920-4dce-a9a5-5ffa085b2e4f" />

# Result
Thus, the python program for addition is tested using pytest and executed and output is verified successfully.
