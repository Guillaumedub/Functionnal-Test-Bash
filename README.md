# Functionnal-Test-Bash

## ex00 - Create bash executable
Create a simple bash file named `my_test.sh` that can be executed and that does nothing

## ex01 - Manage argument in bash
Now that you can execute your bash file, make it print `[PASS]` if we give you 1 argument or `[FAIL]` otherwise.  
For example `my_test.sh` will print `[FAIL]`  
For example `my_test.sh arg` will print `[PASS]`  

## ex02 - Check file existence
Extend the functionality of my_test.sh to perform the following:
    Check if a file named file_to_check.txt exists in the workspace directory.
    Print [PASS] if the file exists.
    Print [FAIL] if the file does not exist.

## ex03 - Check the return value of a program
Now you can improve your bash program to test if a program has returned 0 or 84.
Use the given binary `ret_0` and `ret_84` and check if `ret_0` returns 0 and `ret_84` returns 84.

## ex04 - Naming tests
Now create a function to print a name for each test and numero of the test in the following format:
`test[INDEX]: TEST_NAME`

`./my_test.sh` will print
```sh
test[1]: return value of 0
[PASS]
test[2]: return value of 84
[PASS]
```

## ex05 - Compare the output of a program
Try to compare the output of the given program (hello binary) with your bash file. Check if the hello program prints the following string "Hello, World!\n". If its does `my_test.sh` will print 
```sh
[PASS]
```
else it will print
```
[FAIL]
```
## 06 - Progession bar and color
Now you can try to make a progression bar to have something visual to see how many tests you pass. Below 25% the percentage is displayed in red, between 25 and 75% the percentage is displayed in orange and above 75% the percentage is displayed in green. Also, write "[FAIL]" in red and "[PASS]" in green. 

## 07 - Crash detection
Now your bash file should be supposed to detect a crash. When a test crashes it will display "[CRASH]" in red. For example, if it's a segmentation fault print "[CRASH]". It should work with every crash seg fault, aborded core dump, etc. 

## Bonus
Try to make functional tests for your current project!
