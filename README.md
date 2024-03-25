# Functionnal-Test-Bash

## ex00 - Create bash executable
Create a simple bash file named `my_test.sh` that can be executed and that do nothing

## ex01 - Manage argument in bash
Now that you can execute you bash file, make it print `[PASS]` if we give you 1 argument or `[FAIL]` otherwise.  
For example `my_test.sh` will print `[FAIL]`  
For example `my_test.sh arg` will print `[PASS]`  

## ex02 - Check file existence
Extend the functionality of my_test.sh to perform the following:
    Check if a file named file_to_check.txt exists in the workspace directory.
    Print [PASS] if the file exists.
    Print [FAIL] if the file does not exist.


-----------------------        A MODIFIER
## ex02
Now you can improve your bash program to test if a program has returned 0 or 84.
Use the given binary `ret_0` and `ret_84` and check if `ret_0` returns 0 and `ret_84` returns 84.

## ex03
Now create a function to print a name for each test and numero of the test in the following format:
`test[INDEX]: TEST_NAME`

`./my_test.sh` will print
```sh
test[1]: return value of 0
[PASS]
test[2]: return value of 84
[PASS]
```

## ex04
TEST OUTPUT OF A PROGRAM
