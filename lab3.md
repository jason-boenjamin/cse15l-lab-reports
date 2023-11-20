# Lab Report 3
## By Jason Boenjamin
### This lab report is about Bugs and Commands (Week 5)

<br>
Part 1 - Bugs
<br>
- ***Failure-inducing input for the ArrayExamples buggy program: ***

```
        @Test
        public void testReverseInPlace2(){
        int [] input1 = {1,2,3,4};
        ArrayExamples.reverseInPlace(input1);
        assertArrayEquals(new int[]{4,3,2,1},input1);
        }
```

- ***Non-failure inducing input***
```
        @Test
        public void testReverseInPlace() {
            int[] input1 = { 3 };
            ArrayExamples.reverseInPlace(input1);
            assertArrayEquals(new int[]{ 3 }, input1);
        }
```

- ***Output (failure inducing input test output and non-failure inducing input test output)***

![Image](CSE15_Lab3_SC1.png)

- The first test that we implemented was a simple {1,2,3,4}, where the expected answer was 3.0.
We fixed the test case and we compiled without errors. Then, my lab partner found that the program
would break if there were duplicates of the lowest number.
The symptom that we are testing for is invalid output.

- ***Successful Input:***
```
  @Test
  public void testReversed() {
    int[] input1 = { };
    assertArrayEquals(new int[]{ }, ArrayExamples.reversed(input1));
  }
```



}

<br>
Part 2 - Researching Commands
<br>


- Command 1
```
grep - i "1" *.java
```
  - Looks for every single instance of the given string "1" in all .java files in the current directory.
![Image](CS15L-LAB3-IMG1.png)

- Command 2
```
[cs15lfa23ae@ieng6-201]:lab3:493$ grep -c 1 ListExamples.java
11
[cs15lfa23ae@ieng6-201]:lab3:494$
```

