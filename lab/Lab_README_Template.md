<h1> Lab 00 -- Getting Started with Java and Git </h1>

<h2> Table of Contents </h2>

<!-- TOC -->
  * [`I. DEADLINES`](#i-deadlines)
  * [`II. RESOURCES`](#ii-resources)
  * [`III. PURPOSE`](#iii-purpose)
  * [`IV. DESCRIPTION`](#iv-description)
    * [`DETAILS`](#details)
    * [`STEPS`](#steps)
      * [`DRIVER 1 WRITES CODE`](#driver-1-writes-code)
      * [`DRIVER 2 WRITES CODE`](#driver-2-writes-code)
      * [`DRIVER 1 AND DRIVER 2`](#driver-1-and-driver-2)
  * [`V. SUBMISSIONS`](#v-submissions)
    * [`REFLECTION IDEAS`](#reflection-ideas)
<!-- TOC -->

<h4> 🔵 Understand the problem and Design before Coding 🔵 </h4>

**🔵 Post any questions on [Discord Lab Channel](https://discord.com/channels/1325897175544369263/1325897175544369272) 🔵**

---

## `I. DEADLINES`

| Deliverable | Due Date        |
|-------------|-----------------|
| Lab 00      | Before next lab |
---

## `II. RESOURCES`

- [Class Examples Repo](https://github.com/SP25-ZJY/CS212)
- [Self or Annotated Notes](https://moodle.loyola.edu/course/view.php?id=89009)
- [CS 212: Book](https://open.umn.edu/opentextbooks/textbooks/java-java-java-object-oriented-problem-solving)
- [Solutions To Previous Labs and PAs](https://classroom.github.com/classrooms/193636664-sp25-zjy-cs212)

**🟠 LLM-Based Codes Will Result in Penalty and Honor Code Violation 🟠**

---

## `III. PURPOSE`

The goal of this assignment is to ease you into Java programming using IntelliJ, an Interactive Development Environment (IDE).

This assignment will help you practice the following:

1. Collaborating with your classmate using pair programming.
2. Sharing code through GitHub.
3. Learning about ASCII art.

[<h2>⬆ Back To Top ⬆</h2>](#i-deadlines)

---

## `IV. DESCRIPTION`

Write a simple Java program that prints your initials in the form of ASCII art, similar to the examples found at [ASCII Art](https://www.asciiart.eu/).

### `DETAILS`

- Work in “pair programming” mode. One person is the driver, and the other is the navigator.
- Switch roles after completing the initial code and testing.
- Collaborate effectively by sketching the ASCII art on paper first.

### `STEPS`

#### `DRIVER 1 WRITES CODE`


1. CLONE REPOSITORY: Open IntelliJ and follow the steps in the [“Get a repository from Git to IntelliJ”](https://github.com/SP25-ZJY/CS212/blob/main/SETUP_GUIDE.md) guide under configuration.
    - ⚠️ NO NEED TO INSTALL SWs. AVAILABLE ON LAB PC
2. STATER FILE: There is a single .java file in the repository (HelloWorld.java).
    - Compile and run your program. It should print out Hello, World!.
    - Refer to the guide from the last step if you have any problem.
3. CODE: You will need to modify the `println` statement
    - Add other `println` statements to print out your partner’s name and a fun fact about them, and
    - Add initial (in ascii art).
    - Again, I highly recommend sketching the letters out on paper first.
4. RUN and TEST: Run your program by clicking on the “Run” menu, then -> “Run” or use the Run button.
    - Look at the output at the bottom of IntelliJ.
    - Does it appear the way you want? If not, or if instead you see an error, try to fix your code so that it does what you want (you will need to run again afterward).
    - One of the error you may encounter is “java: illegal escape character” If you have \ (backslash) in your `println` statement, you need to but another one infront of it: \\.
5. CONTINUE CODING: repeat step 4 until you are happy with the result.
6. COMMIT And PUSH: Commit and push your code to github.com.
    - Follow the directions in the “GitHub Quick Guide” document for “Saving Your Work.”

⛔️ If you are happy with the result **_Push and Commit_**
<h2> Now you can switch role. </h2>

[<h2>⬆ Back To Top ⬆</h2>](#i-deadlines)

#### `DRIVER 2 WRITES CODE`

7. CLONE or PULL: It is now driver 2's turn to write the code.
    - They should first Clone the Repository if they haven't already.
    - If you have cloned the repository already before Driver #1 committed and pushed the code.
    - You will need to update your local repository by using the blue arrow on the top menu (Next to Git:)
8. CONTINUE CODING: You should see the changes your partner made in HelloWorld.java.
    - It is now time to write code to print out your partner’s initial.
    - repeat step 3,4 and 5 until you are happy with the result.
9. COMMENT: Comments are part of the programming in general.
    - You should always put comment in your code code.
    - They are used to explain how the code works to human readers of the code.
    - Once your program runs properly, add introductory comments at the very top of your file that match the ones below but are edited to be personalized to you and your partner.
    - Use `//` to add comments to your code.

```
  // Programmers:  your name here
  // Course:  CS 212, Dr. Zelalem Jembre Yalew 
  // Due Date: put the due date here
  // Lab Assignment: 0
  // Problem Statement:  Output programmers’ name, fun facts and initial
  // Input: None, there is no user input in this program
  // Output:  The initials of the programmers in ascii art form
  // Credits: [Is your code based on an example in the book, in class, or something else?  
  //            Reminder: you should never take code from the Internet or another person
```
---

#### `DRIVER 1 AND DRIVER 2`

10. Make sure to indent your code properly and there is no error.

11. COMMIT And PUSH: Commit and push your code to github.com.
    - Follow the directions in the “GitHub Quick Guide” document for “Saving Your Work.”

Quick note:

**If you are done,  show your program running and on GitHub to the professor before leaving the classroom.**

---

## `V. SUBMISSIONS`

**🔶 Commit and Push to GitHub: 🔶**

1. Completed `HelloWorld.java` file.
2. Encrypted reflection files using the `FET.java`:
    - `RD1.md`: Reflection for Driver 1.
    - `RD2.md`: Reflection for Driver 2.
    - `RD3.md`: Reflection for Driver 3. (If there are three members)

---

### `REFLECTION IDEAS`

Write your reflection in the respective files (`RD1.md` and `RD2.md`). Address the following:

- **Objective**:
    - What were you supposed to learn/accomplish?
- **Procedure**:
    - What steps were followed?
    - What techniques were used to solve the problem?
- **Results**:
    - Did your results meet your expectations?
    - Did you test with extreme or edge cases?
- **Reflection**:
    - What challenges did you encounter?
    - How did you address them?
    - What was it like working with your partner?

[<h2>⬆ Back To Top ⬆</h2>](#i-deadlines)