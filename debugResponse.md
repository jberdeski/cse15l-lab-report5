# Debugging Scenario

## Question

**Can't Run Tests**

**Category:** Debugging

**What environment are you using (computer, operating system, web browser, terminal/editor, and so on)?**

Computer: ROG STRIX

OS: Windows 11

Program: Visual Studio Code

Terminal: Bash

**Detail the symptom you're seeing. Be specific; include both what you're seeing and what you expected to see instead.
Screenshots are great, copy-pasted terminal output is also great. Avoid saying “it doesn't work”.**

![bugs Ew](buggyTerminal.png)

I expected for my tests to run, I have two tests in ArrayTests.java but the output says only one runs and I'm not sure why.

**Detail the failure-inducing input and context. That might mean any or all of the command you're running, a test case, command-line arguments, working directory, even the last few commands you ran. Do your best to provide as much context as you can.**

The terminal says that is is caused by multiple things such as; ClassNotFoundException, BuiltInClassLoader, etc. My class is correctly spelled in the command and my tests seem to be correct:
![ArrayTests Code](arrayTestsCode.png)

## Response
Interesting! You notice the errors and I agree that your class is spelled correctly in the command. The issue lies in the format of your java command. 
Take a look at the commands here: [](https://ucsd-cse15l-s23.github.io/week/week3/#setup)

Do you notice anything different about what you have and what is there?

## What Happened? 
When you look at the code in the link provided you may have noticed that your issue was simply adding .java at the end of your java command. 
