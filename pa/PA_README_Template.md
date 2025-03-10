<h1> CS212 Programming Assignment 0 </h1>

<h2> Table of Contents </h2>

<!-- TOC -->
* [`I. DEADLINES`](#i-deadlines)
* [`II. RESOURCES`](#ii-resources)
* [`III. PROBLEM`](#iii-problem)
* [`IV. PURPOSE OF THE ASSIGNMENT`](#iv-purpose-of-the-assignment)
* [`V. REQUIREMENTS ANALYSIS`](#v-requirements-analysis)
* [`VI. DESIGN`](#vi-design)
* [`VII. PROGRAMMING REQUIREMENTS`](#vii-programming-requirements)
* [`VI. STYLE`](#vi-style)
* [`IX. SUBMISSIONS`](#ix-submissions)
   * [`DESIGN SUBMISSION: Sunday 01/20 11:59PM`](#design-submission-sunday-0120-1159pm)
   * [`FINAL SUBMISSION: Monday 01/27 11:59PM`](#final-submission-monday-0127-1159pm)
   * [`REFLECTION IDEAS`](#reflection-ideas)
   * [`REMINDERS`](#reminders)
<!-- TOC -->

<h4> 🔵 Understand the Problem and Design Before Coding 🔵 </h4>

**🔵 Post any questions on [Discord PA Channel](https://discord.com/channels/1325897175544369263/1325897175544369271) 🔵**

---

## `I. DEADLINES`

| Deliverable | Due Date             |
|-------------|----------------------|
| PA-Design   | Sunday 01/20 11:59PM |
| PA-Final    | Monday 01/27 11:59PM |

---

## `II. RESOURCES`
- [Class Examples Repo](https://github.com/SP25-ZJY/CS212)
- [Self or Annotated Notes](https://moodle.loyola.edu/course/view.php?id=89009)
- [CS 212: Book](https://open.umn.edu/opentextbooks/textbooks/java-java-java-object-oriented-problem-solving)
- [Solutions To Previous Labs and PAs](https://github.com/SP25-ZJY)


- **You can use LLM (Such as ChatGPT or Gemini) as a guider but not as a problem Solver**  
  🟠**LLM-Based Codes Will Result in Penalty and Honor Code Violation**🟠

- ⚠️ **To edit the flow chart file, add `diagrams.net` plugin** ⚠️
   - File -> Settings -> Plugins -> Marketplace: Then search and install `diagrams.net`.
   - Update the flowchart of your project using [`Flow Chart`](uml.drawio.svg).

---

## `III. PROBLEM`
For this assignment, you will add some functionality to your ATM in one of your previous labs. Your ATM will now support multiple accounts and even let you view your account history.

---

## `IV. PURPOSE OF THE ASSIGNMENT`
The purpose of this assignment is for you to gain experience with:

1. designing your own class
2. practicing with arrays
3. working with multiple .java files
4. using proper Java documentation

[<h2>⬆ Back To Top ⬆</h2>](#i-deadlines)

---

## `V. REQUIREMENTS ANALYSIS`
The first stage in your programming assignment is the requirements analysis stage.  You need to make sure you understand the below requirements:

For this assignment, you are going to create an ATM named Greyhound Teller Machine (GTM).

The ATM will behave as follows (**NOTE:** this is not a proper algorithm):

1. The ATM asks for a user's first and last name or "exit"
2. If the user selects exit
   1. End the program
3. Look up the user's account number using their name.
4. If the user is not in the system and there is at least one unused account.
   1. A new account is created for them.
5. Otherwise, if there are no spaces remaining:
   1. Go to step 1
6. Otherwise,
   1. The user's account is retrieved.
7. The user's account number is displayed.
8. The user is provided a menu to *withdraw*, *deposit*, *get statistics*, *view recent transactions*, or *leave*.
9. While the user has not chosen to leave:
   1. If a user selects **deposit**
      1. The ATM should increase the user's balance by the provided positive amount
   2. Otherwise, if a user selects **withdraw**
      1. The ATM should reduce the balance by the users provided a positive amount if and only if there are sufficient funds.
   3. Otherwise, if the user selects **get statistics**
      1. The ATM should display the current balance, as well as the min, max, and average transaction sizes of the last 5 transactions.
   4. Otherwise, if the user selects **view recent transactions**
      1. The ATM should show the user their last 5 deposits or withdrawals (or fewer if they have not made 5 yet).
10. Go to step 1

### Account Class
For this assignment, you will create a class that encapsulates a bank account. It is up to you how to design and implement the **Account** class. However, it should have the following minimum requirements:

#### Attributes (Data Fields/Instance variables)

1. An array to track the previous 5 transactions
2. A string for the name of the account owner
3. *Any other data members you think you might need.*

#### Methods

1. A constructor with the number of recent transactions to store, an initial deposit, and the name of the owner.
2. `isOwner` method to determine if an account is owned by a given person.
3. `deposit` method to initiate a deposit
4. `withdraw` method to initiate a withdrawal
5. `getStats` method to return an array of statistics
6. `toString` or `display` method to assist in printing our account information

### Main

You will also write a client class (Main) to use the `Account` class. The `main` program should behave as described above.

#### Additional details
* The ATM supports 5 customers which should be stored in an array.
* The "account number" is the index of the Account in the ATM's array.

### Other classes
You can create other classes to support the ATM as you see fit. **If you do, you need to include it in DESIGN.md**

---

## `VI. DESIGN`
The second stage is to design your solution based on the requirements:

1. The design should not include any code.

2. Write out your class design in DESIGN.MD
   1. Start with listing all the attributes (with data type and purpose).
   2. Then list the default and other constructors with their required parameter
   3. Do the same for other methods: purpose, list of parameters, and return value.
   4. Also include the access modifier for all of them.
3. Draw a UML diagram of your class, this should reflect what you have in your design.

---

## `VII. PROGRAMMING REQUIREMENTS`
After your design is complete and correct, it's time to start programming and then testing:

1. Fix design issues: If there were issues with your design, either not meeting requirements or in the format, fix that before you start writing your code.
2. Implementation: Write your program following the requirements and based on your design. Name your source code appropriately.
   1. Follow good usability/HCI principles in your input and output (for instance, make it clear the type of input you are asking for).
   2. Remember to state the purpose of the program.
3. Testing: Make sure it works correctly; give it sample input, and check that the output is correct.

### Error checking
You should do at least the following error checking:
1. The user should not be able to select invalid menu options.
2. The user should not be able to enter negative numbers or zero for deposits or withdrawals.
3. The program should not crash if the user enters something that is not a number.

### Extra Credit
Do not attempt this until everything else is working.

Add a secret menu option: *hacker*. When this option is selected it should print out the statistics of all the account owners sorted from greatest bank balance to least. It should do this without changing the order of the account array so as not to change the account numbers.


[<h2>⬆ Back To Top ⬆</h2>](#i-deadlines)

---

## `VI. STYLE`
Follow these style guidelines:

1. **File headers**: Include at the top of each file:
   ```java
    /**
    * This is my code! It's goal is to <give purpose of file here>
    * CS 212 - Lab <#>
    * @author <Your Name> <Your partner name>
    * @version <a version number followed by a date>
    */
   ```

2. **Variable names**: Use meaningful camelCase names.
3. **Code formatting**: Use consistent indentation, whitespace, and alignment.
4. **Documentation**: Add comments for clarity.
5. Every method in your class must have a header comment of the form (replace the bits in < > and only use the number of `@param` that are needed for your method):
    ```java
       /**
       * <A one sentence description of the method, ending with a period.>
       * <Optional longer description if desired>
       *
       * @param  <first parameter name>  <purpose of the parameter>
       * @param  <second parameter name>  <purpose of the second parameter>
       * @return      <what is returned>
       */
    ```
6. Your code should have no compilation errors.
5. **Git usage**: Commit after milestones with meaningful messages.
   - Avoid a single commit for the entire project.
   - use meaningful commit messages and commit after reasonable milestones (i.e., default constructor has been completed)


## `IX. SUBMISSIONS`

### `DESIGN SUBMISSION: Sunday 01/20 11:59PM`
**🔶 Commit and Push to GitHub: 🔶**

1. Submit the following:
   - [`initial_design.md`](initial_design.md): Your initial algorithm.
   - [`uml and/or flowchart`](flowchart_uml.drawio.svg): UML and/or Flowchart in SVG format.
      - If you work on your personal computer add `diagrams.net` plugin
         - File -> Settings -> Plugins -> Marketplace: Then such and install `diagrams.net`

           > N.B. If you can not see the shapes after the setup, toggle to editor mode

           ![](editor.png)

           > **SEE THE MEANING AND THE DESIGN OF UML FOR DICE CLASS**

           ![](uml_meaning.png)

2. Your design document should:
   - Follow all requirements outlined in the assignment.
   - Include the full story and logical steps.
   - **Contain no code.**

**✅ Ensure all files are pushed to GitHub and visible in your repository. ✅**

---

### `FINAL SUBMISSION: Monday 01/27 11:59PM`
**🔶 Commit and Push to GitHub: 🔶**

1. Submit the following:
   - [`.java`](`*.java`): Your program's source code.
   - [`initial_design.md`](initial_design.md): Your original design document.
   - [`final_design.md`](final_design.md): Updated design reflecting changes during development.
   - [`test_cases.xlsx`](test_cases.xlsx): Your test cases in Excel format.
   - [`uml and/or flowchart`](flowchart_uml.drawio.svg): Visual UML or Flowchart of your program.
   - [`reflection.md`](reflection.md): Reflection document addressing the questions below.

2. Ensure all files are:
   - **Correctly named** and placed in your project folder.
   - **Pushed to GitHub** and verified on `github.com`.
   - Use **meaningful commit messages** for each milestone.
---

[<h2>⬆ Back To Top ⬆</h2>](#i-deadlines)