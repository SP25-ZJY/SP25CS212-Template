<h1> CS151 PROGRAMMING ASSIGNMENT 0</h1>

<h2> Table of Contents </h2>

<!-- TOC -->
* [`I. DEADLINES`](#i-deadlines)
* [`II. RESOURCES`](#ii-resources)
* [`III. PURPOSE OF THE ASSIGNMENT`](#iii-purpose-of-the-assignment)
* [`IV. PROBLEM`](#iv-problem)
* [`V. REQUIREMENTS ANALYSIS`](#v-requirements-analysis)
* [`VI. DESIGN`](#vi-design)
* [`VII. PROGRAMMING REQUIREMENTS`](#vii-programming-requirements)
* [`VIII. ASSIGNMENT REMINDERS`](#viii-assignment-reminders)
* [`IX. SUBMISSIONS`](#ix-submissions)
    * [`DESIGN SUBMISSION: Sunday 01/20 11:59PM`](#design-submission-sunday-0120-1159pm)
    * [`FINAL SUBMISSION due Monday 01/27 11:59PM`](#final-submission-due-monday-0127-1159pm)
<!-- TOC -->

<h4> 🔵 Understand the problem and Design before Coding 🔵 </h4>

**🔵 Post any question on [Discord PA Channel](https://discord.com/channels/1316435150527004825/1316435267145695312) 🔵**
## `I. DEADLINES`

| Deliverable | Due Date             |
|-------------|----------------------|
| PA-Design   | Sunday 01/20 11:59PM |
| PA-Final    | Monday 01/27 11:59PM |

## `II. RESOURCES`
- [Class Examples Repo](https://github.com/SP25-ZJY/CS151)
- [Self or Annotated Notes](https://moodle.loyola.edu/course/view.php?id=89004)
- [CS 151: Book](https://learn.zybooks.com/zybook/LOYOLACS151Spring2025)
- [Solutions To Previous Labs and PAs](https://classroom.github.com/classrooms/193636664-sp25-zjy-cs151)
- [PA Late Submission Form](https://forms.office.com/r/mkE8wwT1xV)
- **You can use LLM (Such as ChatGPT or Gemini) as a guider but not as a problem Solver**
    - 🟠**LLM-Based Codes Will Result in Penalty and Honor Code Violation**🟠

## `III. PURPOSE OF THE ASSIGNMENT`

This assignment is aimed at:

1. Providing you an opportunity to use mathematical expressions, input, and output in Python.
2. Giving you the opportunity to design a program.
3. Providing you with an opportunity to plan for testing your program.
4. Practicing soliciting and using input from the user.

## `IV. PROBLEM`

Most people who develop computer software don’t do it for themselves or for an instructor’s imaginary scenario.
- Most programs are written to solve a problem or answer a real need.
- Even though you don’t know all of Python, you will know enough to write a simple program that does a calculation that could be helpful to someone else.

Find a simple mathematical calculation that is of use to someone else (a friend, a parent, a sibling).
- The first step is to ask the person and get a clear idea of the need
    - 🟢No fair assuming your program will be helpful—you need to actually ask!.🟢
- Your program must ask for input values for the calculation, do the calculation, and output the result.

🟡Example: Finding the area and circumference of a circle given the radius.🟡

**🔴Not allowed: You may not solve a problem that is solved in the textbook, or a problem you see in class, lab, or prep!🔴**

[<h2>⬆ Back To Top ⬆</h2>](#i-deadlines)

## `V. REQUIREMENTS ANALYSIS`

The first stage in your programming assignment is the requirements analysis stage. You need to:

1. Find someone who needs a set of mathematical calculations done.
    - It must require more than one mathematical operation (i.e., you can’t just add 2 numbers together).
2. Think about what you need to do to solve their problem.
    - What information do you need to gather, and how do you correctly calculate what they need to calculate?
3. Gather the information you need to solve their problem.

## `VI. DESIGN`

The second stage is to design your solution:

1. Ensure you understand how to solve the problem correctly.
    - If you don’t understand the problem steps or make incorrect assumptions, your algorithm won’t solve the problem.
2. Write out your algorithm, including input, output, and calculations.
3. Test your algorithm to ensure it solves the problem correctly.

✳️To be done on [`initial_design.md`](initial_design.md) document via a markdown:✳️
- A description of the problem you will solve.
- The name of the person you are solving it for and their relation to you.
- A reference for where you looked up the calculation for the problem (could be a web link, a textbook, etc.).
- The algorithm for your program, including input, output, and calculations.

## `VII. PROGRAMMING REQUIREMENTS`

After your design is complete, follow these steps:

1. **Implementation**: Write your program on [`main.py`](main.py) following the below requirements and based on your design:
    - The user must input at least one number needed for the calculation.
    - Output the answer to the user with text describing the number (good usability).
    - Use mathematical symbols and functions correctly.
2. **Testing**:
    - Create a list of inputs and the correct output covering all possible cases on [`test_cases.xlsx`](../test_cases.xlsx).
    - Test your program with these cases and correct any errors.
3. **Evaluation**:
    - Ask your customer to evaluate your program. Adjust if necessary.
    - See Feedback from professor
    - ✳️ Updates to algorithm at this point will be done on [`final_design.md`](final_design.md) ✳️

[<h2>⬆ Back To Top ⬆</h2>](#i-deadlines)

## `VIII. ASSIGNMENT REMINDERS`

- Follow the programming assignment requirements document for comments, formatting, etc.
- Follow the honor code guidelines outlined in the syllabus and at [here](https://www.loyola.edu/academics/computer-science/current-students/honor-code).

- Include intro comments.

```
# Programmers:  [your names here]
# Course:  CS151, Dr. Zelalem Jembre Yalew
# Due Date: [date assignment is due]
# Assignment:  [number of assignment]
# Problem Statement:  [what problem does your code solve; i.e., calculating inches from centimeters]
# Data In: [what information do you request from the user?]
# Data Out:  [What information do you display for the user?]
# Credits: [Is your code based of an example in the book, in class, or something else?  Reminder: you should never take code from the Internet or another person.]
```
## `IX. SUBMISSIONS`

### `DESIGN SUBMISSION: Sunday 01/20 11:59PM`

**🔶 Commit and Push to GitHub: 🔶**

1. Write the algorithm for your design on [`initial_design.md`](initial_design.md) document.
2. The document can include aspects of the assignment
    1. You think you've correctly included
    2. You are not sure is correct or got stuck on.
    3. Importance of adding description
        1. To make it clear that you understand what you've done, or
        2. Where you need the most help in getting ready to write the code.

Submit an additional file (PDF or image) containing:
- A signed or emailed statement from your user that indicates their need for your software to solve this problem.
- **✅ The document must be in the project folder and pushed to GitHub ✅**

If you decided to design a smarter computer player, note that in your document and why you designed it that way, so that you can get feedback on your design.

Your algorithm should follow the requirements of an algorithm, and contain all the requirements for this assignment. **There should not be any code.**


### `FINAL SUBMISSION due Monday 01/27 11:59PM`
**🔶 Commit and Push to GitHub: 🔶**

1. Completed [`main.py`](main.py) file
2. [`initial_design.md`](initial_design.md)
3. [`final_design.md`](final_design.md)
4. An Excel file with your test cases.
    - Edit the [`test_cases.xlsx`](../test_cases.xlsx) file with Excel software
    - If it can open then ok. Otherwise
        - Right click on [`test_cases.xlsx`](../test_cases.xlsx) -> Open In -> Associated Application
5. [`reflection.md`](reflection.md) -> Reflection of the assignment
6. A signed or emailed statement from a client that they are satisfied with your SW .


**As a reminder, reflections count toward your participation grade.**

Type the Reflection INSIDE the respective [markdown file](reflection.md) and addressing the following questions:

- Objective:
    - What were you supposed to learn/accomplish?

- Procedure:
    - What steps were followed and what techniques did you use to solve the problem?
    - What were the Key concepts explored?

- Results:
    - Did your results match what you expected to get?
    - Did you try using various test cases, or extreme test cases?

- Reflection:
    - What challenges did you encounter?
    - How did you follow the first 3 rules of programming?
    - Did you overcome them, and how?
    - Any key takeaways?
    - Do you think you learned what you were supposed to learn for this lab?
    - What was it like working by yourself?

***Remember to commit and push your GitHub project.***

[<h2>⬆ Back To Top ⬆</h2>](#i-deadlines)

✅✳️⬅️➡️⏺️🔼🟢🟡🔴🔵🟣🟠⛔️🟥🔶🔻🔺❌‼️❕
