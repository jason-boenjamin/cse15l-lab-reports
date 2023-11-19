# Lab Report 4
## By Jason Boenjamin
### VIM

Steps 4 - 9

4. Log into ieng6
![Image](CSE_Lab4_SC1.png)
- I sshed into my ieng6 account.

5. Clone your fork of the repository from your Github account
![Image](CSE_Lab4_SC2.png)
- I made a temporary directory for this lab
- I then used `cd` to change into the directory
- I `git clone` from my github account for lab 7

6. Run the tests, demonstrating that they fail
![Image](CSE_Lab4_SC3.png)
- I used the command `vim ListExamples.java` to make sure I cloned the right version.
- I used the command `bash test.sh` to run the test and show that they failed

7. Edit the code file to fix the failing test
![Image](CSE_Lab4_SC4.png)
- I used the command `vim ListExamples.java` to go into the file
- I pressed [:44] to go to line 44, where the error was.
![Image](CSE_Lab4_SC5.png)
- I used the command `de` which means to delete to (including) end of word.
- Then, I pressed [i] to go into insert mode.
![Image](CSE_Lab4_SC6.png)
- I pressed <esc> to enter command mode
- I typed in the command `:wq`. [w] means to save or write and [q] means to quit.

8. Run the tests, demonstrating that they now succeed
![Image](CSE_Lab4_SC7.png)
- I used the command `bash test.sh` to run the tests, demonstrating that they now succeed.
    
8. Commit and push the resulting change to your Github account (you can pick any commit message!)
![Image](CSE_Lab4_SC8.png)
- I used the command `git commit`, where I added my messages for my changes

![Image](CSE_Lab4_SC9.png)
- Finally, I used the command `git push` to push the resulting change to my Github account.
