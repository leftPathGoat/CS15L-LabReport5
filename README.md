# CS15L-LabReport5
**Part 1 – Debugging Scenario**
**What environment are you using (computer, operating system, web browser, terminal/editor, and so on)?**

*I am using Windows and VSCode for my text editor.*

**Detail the symptom you're seeing. Be specific; include both what you're seeing and what you expected to see instead. Screenshots are great, copy-pasted terminal output is also great. Avoid saying “it doesn't work”.**

*I am writing a static method `min` in the class `findMin`. The method is designed to take an arraylist of integers and multiply return the smallest element. Most of  JUnit test approved my implementation. However, some Junit test shows that the method has wrong output for specific inputs.*

**Detail the failure-inducing input and context. That might mean any or all of the command you're running, a test case, command-line arguments, working directory, even the last few commands you ran. Do your best to provide as much context as you can.**

*Here is a screenshot of the failed test and all my files. The tests are in `TransformerTest.java` and the implementation is in `Transformer.java`.*
![bug.png](images/bug.png)
*When I run `bash test.sh`, which basically just compiles with JUnit and runs the test, I get the following output:*
