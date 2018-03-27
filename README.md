# CodeCheck
Simple program that checks outputs of an executable file against input/output text files

# Instructions
* Compile test.c
```
gcc -o test test.c
```
* Compile required executable file (here, evenodd.c is a program that checks whether a given number is odd or even)
```
gcc evenodd.c
```
* Enter test cases into testcase.txt (here, a bunch of numbers)
* Enter expected outputs for the test cases in correct.txt (here, even or odd)
* Run ./test (returns 1 on correct output, returns 0 on incorrect output)

