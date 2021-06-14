# Practice Exam 1

## Basic Info

- Date: 6 March 2021 (Saturday)
- Time: 9 am to 12noon (Report to invigilator at 9 am, exam starts at 9:30am)
- Format: Face-to-face.
- Venue: PL1/PL2
- Scope: Units 1-12, Assignments 1-2, Tutorials 1-4
- 5 programming questions: from very easy to very hard
- Criteria: correctness, style, efficiency, and documentation.  These are applied differently to different question (e.g., efficiency is important only for some questions, documentation is required only for some questions).
- Duration: 2 hours and 30 minutes
- Open Book (You can refer to printed/written materials, but no online resources are allowed).

## Special Restrictions

- **(New!) Remember to bring your student card for verification purposes.**
- You will need to attend the PE at a specific programming lab. Please refer to the Allocation Section below for more information.
- You will be issued a special account on the actual day for the practical exam. 
- You will need to log into a special set of PE nodes through `ssh` to solve the exam questions.  
- You are not allowed to use the Internet for other purposes.  You are only allowed to (i) interact with the files on the PE nodes through `ssh`; and (ii) communicate with the invigilators.  File transfer into the PE nodes is not allowed.  
- You are allowed to ask clarification questions during the exam.  However, you may only ask a boolean yes/no question.  For instance, you are not allowed to ask "What can we assume about the input?".  You should rephrase it as "Can we assume that the input is always positive?".  Our answers will only be in the form of "yes", "no", "no comment".

## Vim Configuration

Your default account will have the same `.vimrc` as `~cs1010/.vimrc` on the CS1010 PE hosts.  

You are free to edit this during the practical exams.  

You, however, will not be able to download nor install `vim` plugins.

## Allocation

- T01/T03/T04: PL2 @ COM1-B109
- T05/T07/T10/T11: PL1 @ COM1-B112

## Invigilators

Adhy, Gizem, Felix, Francisco, Ryan

## General Advice

- Save your program regularly.  We will use setup every account with `~/.vimrc` copied from `~cs1010/.vimrc`.  Thus, you can find the last saved version of your files under `~/.backup` if you accidentally deleted your code.
- Plan your time properly.  Do not spend excessive time on any task.  Read through all questions and solved those that you are confident to solve first.
- There are five questions, from very easy to very hard.  Solve as many as you can.  I expect most students will be able to solve 3 out of the 5 questions within the time limit.
- There is one mark allocated to style for each question.  As long as you keep your code clean, neat, and readable, you will get this one mark, almost for free.  Review the CS1010 style guide so that you know what is expected in terms of coding style.
- Don't start typing your code right away.  Think about the solution first -- what variables are needed?  What is the control flow (using branches and loops)?  Draw out the flowchart if it helps.  
- Break down the problem into smaller ones if the problem is too complex to solve.
- You are not allowed to start typing on the computer until the invigilator announced that you can do so.
- Just like the assignments, you are not given all the test cases that we will be using during grading.  Please test your code against additional test cases, especially for boundary cases.

## Practice Paper

You can use the PE questions from 20/21 Semester 1 as the practice paper.

- [Accept the assignment](https://classroom.github.com/a/SzMkmuU3) on GitHub
- Run `~cs1010/get-pe98` on any PE host to get the skeleton code and test cases
- Run `~cs1010/submit-pe98` to submit/archive your solution on GitHub

You can now re-attempt the PE questions of this semester for your own practice.

- [Accept the assignment](https://classroom.github.com/a/ahKckD1w) on GitHub
- Run `~cs1010/get-pe01` on any PE host to get the skeleton code and test cases
- Run `~cs1010/submit-pe01` to submit/archive your solution on GitHub