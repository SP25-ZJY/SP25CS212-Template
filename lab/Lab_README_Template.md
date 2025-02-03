<h1> Lab 02 -- A Greyhound Grocers Cashier </h1>

<h2> 50 Points </h2>

<h2> Table of Contents </h2>

<!-- TOC -->
* [`I. DEADLINES`](#i-deadlines)
* [`II. RESOURCES`](#ii-resources)
* [`III. PURPOSE`](#iii-purpose)
* [`IV. PROBLEM`](#iv-problem)
* [`V. DETAILS`](#v-details)
* [`VI. REQUIREMENTS`](#vi-requirements)
    * [Quick note:](#quick-note)
    * [Bonus:](#bonus)
* [`VII. REMINDERS`](#vii-reminders)
* [`V. SUBMISSIONS`](#v-submissions)
<!-- TOC -->

<h4> ⛔️ Do Not start coding before completing your algorithm ⛔️ </h4>

<h4> 🔵 Understand the problem and Design before Coding 🔵 </h4>

**🔵 Post any questions on [Discord Lab Channel](https://discord.com/channels/1325897175544369263/1325897175544369272) 🔵**

---

## `I. DEADLINES`

| Deliverable | Due Date        |
|-------------|-----------------|
| Lab 02      | Before next lab |
---

## `II. RESOURCES`

- [Class Examples Repo](https://github.com/SP25-ZJY/CS212)
- [Self or Annotated Notes](https://moodle.loyola.edu/course/view.php?id=89009)
- [CS 212: Book](https://open.umn.edu/opentextbooks/textbooks/java-java-java-object-oriented-problem-solving)
- [Solutions To Previous Labs and PAs](https://classroom.github.com/classrooms/193636664-sp25-zjy-cs212)

**🟠 LLM-Based Codes Will Result in Penalty and Honor Code Violation 🟠**
## `III. PURPOSE`

In this assignment, practice using flow controls (if-else-loop), input (Scanner), and output.

## `IV. PROBLEM`
You will develop a program that acts as a smart ATM

## `V. DETAILS`
You work at a bank and your current project is to design and implement a new interface for a new generation of ATMs.
> Your task is to write a Java program to interact with a customer who wants to **deposit** to, **withdraw** from, and **check the balance** of their bank account.

>The interface needs to prompt for a customer name and print out a greeting message. It then asks the customer what he/she wants to do.

```
1. Deposit
2. Withdraw
3. Check Balance
4. Exit
```

Your program should be able to do the support:

1. A customer can make more than one transaction.
2. The interface needs to prevent the customer from **withdrawing** money if there is insufficient funds.
3. When the customer finishes, print out a summary of all transactions (total amount deposit or/and withdraw) and a thank you message.
4. At the end, remind them to take the receipt or check their email the confirmation.

## `VI. REQUIREMENTS`

1. Complete program in [Main.java](Main.java).
2. Complete set of [test cases.xlsx](test_cases.xlsx).
    - You may use the Excel file help you with the calculation.
2. Complete an algorithm before you program [algorithm.md](algorithm.md).
3. Follow good programming practices including pair programming
    - `When 1/2 the code is written, or 1/2 of class is over, switch drivers.`
4. Ensure your code meets all detailed requirements.
5. Properly use variables (including ensuring the type is correct), input, math, and output.
6. Use your test cases to test that your program works correctly. Fix any errors.
7. **_FLOWCHART IS REQUIRED_**
    - But First add `diagrams.net` plugin
        - File -> Settings -> Plugins -> Marketplace: Then such and install `diagrams.net`
    - Update the flowchart of your project using `flowchart.drawio.svg`

[<h2>⬆ Back To Top ⬆</h2>](#i-deadlines)

### Quick note:
**This is the assumption about the opening balance**: store the balance in a variable named `balance` and initialize it to `$212.90`

### Bonus:
- You can earn **5 additional points** if you use **switch/case** in your program.

    - **Only attempt this when everything else works**
- You can earn additional bonus points by performing error checking when user enters their choice (1,2,3,4) i.e. entering a non-number will not crash your program.

## `VII. REMINDERS`

You will write your program in the "pair programming" mode: one of you is the driver while the other is the navigator.

1.  ⛔️ Make sure you *understand the problem* you are being asked to solve.
- What are the input(s), output(s), and calculation(s)?
2. ✅ *Write Test Cases*: create a series of test cases in [test_cases.xlsx](test_cases.xlsx) to use to determine that your program works correctly.
    - Double check your test cases. Make sure they cover a wide range of cases.
3. ✅ *Complete the algorithm* in [algorithm.md](algorithm.md).
- **Whoever didn't type the majority of the test cases, should type the algorithm**
- Your program should do ALL of the calculations for you, and it should work for ANY valid inputs.
- You do not need to do error checking, yet.

4. ✅ *Code*: Your code should be in [Main.java](Main.java) and follow your algorithm to write your code.
- You may assume that your input will always be of the correct type.
- Whoever has done the least typing at this point should start as a driver.

5. ❌ *Fix compiler errors*: Run your program and fix any errors that appear.

6. ❌ *Test:* Once your code runs and you think it’s complete, test it using your test cases.
- run, give the input value as input, and see if you get the right output.
- If not, you need to fix the error(s) in your code!

7. ✳️ Make sure you’ve created a human-readable essay (i.e. your program).
- Did you follow the code readability guidelines?
    - If not, fix your code so that it is readable.
- You should have comments above each chunk of code!
- Use white spaces to make your code more readable and lastly be consistent and considerate in naming your variables (**use camel Case style**)

8. ✳️ Include an updated version of the intro comments below at the very top of your .java file.
- Do not include the brackets `[` and `]` but replace them with what is asked for inside of them.
- Be sure to keep the titles at the start of each line.
  ```java
  /**
   * [Brief description of the file's purpose]
   * Due Date: [date assignment is due]
   * Assignment:  [number of assignment]
   * Problem Statement:  [what problem does your code solve; i.e., calculating inches from centimeters]
   * Data In: [what information do you request from the user?]
   * Data Out:  [What information do you display for the user?]
   * @author <Your Name>
   * @version <Version Number, Date>
   */
  ```

9.  Once you are done in lab, even if you haven’t finished the assignment yet, you need to Commit and Push your changes.


## `V. SUBMISSIONS`

**🔶 Commit and Push to GitHub: 🔶**

1. Completed `Main.java` file
2. Your design on `algorithm.md` file
3. flow chart `flowchar.drawio.net` file
4. An Excel file with your test cases.
    - Edit the `test_cases.xlsx` file with Excel software
    - If it can open then ok. Otherwise
        - Right click on `test_cases.xlsx` -> Open In -> Associated Application
5. Encrypted reflection files using the `FET.java`:
    - `RD1.md`: Reflection for Driver 1.
    - `RD2.md`: Reflection for Driver 2.
    - `RD3.md`: Reflection for Driver 3. (If there are three members)
    - N.B. You can get the path of the reflection file and paste it inside the fet browser
    - <img src="enc_steps.png" alt="">

[<h2>⬆ Back To Top ⬆</h2>](#i-deadlines)
