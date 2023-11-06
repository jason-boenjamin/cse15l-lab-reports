# Lab Report 3
## By Jason Boenjamin
### This lab report is about Bugs and Commands (Week 5)

<br>
Part 1 - Bugs
<br>
- Failure-inducing input for the ArrayExamples buggy program:
```
double [] input1 = {1,2,3,4,-1,-1};
double answer = 3;
assertEquals(answer, ArrayExamples.averageWithoutLowest(input1),0.00001);
```
- Output
```
There was 1 failure:
1) testAverageWithoutLowest(ArrayTests)
java.lang.AssertionError: expected:<3.0> but was:<2.0>
```
- The first test that we implemented was a simple {1,2,3,4}, where the expected answer was 3.0.
We fixed the test case and we compiled without errors. Then, my lab partner found that the program
would break if there were duplicates of the lowest number.
The symptom that we are testing for is invalid output.

- Successful Input:
```
double [] input1 = {1,2,3,4};
double answer = 3;
assertEquals(answer, ArrayExamples.averageWithoutLowest(input1),0.00001);
```
Output:


}

<br>
Part 2 - Researching Commands
<br>


- Command 1
```
grep - i "1" *.java
```
- Looks for every single instance of the given string "1" in all .java files in the current directory.
![Image](CSE15L-LAB3-IMG1.png)


