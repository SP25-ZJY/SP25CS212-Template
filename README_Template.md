<h1> CS151 PROGRAMMING ASSIGNMENT 5 </h1>

<h2>Table of Contents</h2>

<!-- TOC -->
  * [`DEADLINES`](#deadlines)
  * [`RESOURCES`](#resources)
  * [`OVERVIEW`](#overview)
  * [`FILE ORGANIZATION`](#file-organization)
  * [`PURPOSE OF THE ASSIGNMENT`](#purpose-of-the-assignment)
  * [`PARTNER AGREEMENT Submission`](#partner-agreement-submission)
  * [`DESIGN Submission`](#design-submission)
  * [`ASSIGNMENT REMINDERS & WORKING AS A PAIR/GROUP`](#assignment-reminders--working-as-a-pairgroup)
  * [`USABILITY`](#usability)
  * [`PROGRAMMING REQUIREMENTS`](#programming-requirements)
  * [`FINAL PRESENTATION `](#final-presentation-)
  * [`Earning an E`](#earning-an-e)
  * [`What to Submit (Commit & Push) in GitHub`](#what-to-submit-commit--push-in-github)
<!-- TOC -->

## `DEADLINES`

| Deliverable                          | Due Date               |
|--------------------------------------|------------------------|
| Partner Agreement and Plan           | Monday 11/25 11:59PM   |
| Design                               | Monday 12/2 11:59PM    |
| Final Project                        | Sunday 12/8 11:59PM    |
| Presentation                         | Monday 12/9 Class time |
| Reflection and Partner Survey        | Monday 12/9 02:00 PM   |

## `RESOURCES`
- [Class Examples Repo](https://github.com/SP25-ZJY/CS212)
- [Self or Annotated Notes ](https://moodle.loyola.edu/course/view.php?id=89009)
- [Java Java Java Book](https://open.umn.edu/opentextbooks/textbooks/java-java-java-object-oriented-problem-solving)
- [Solutions To Previous Labs and PAs](https://classroom.github.com/classrooms/193636664-sp25-zjy-cs212)
- **You can use LLM (Such as ChatGPT or Gemini) as a guider but not as a problem Solver**
- 🟠**LLM Based Codes Will Result in Penalty and Honor Code Violation**🟠

## `OVERVIEW`
The problem to be solved will vary from group to group [PA5 Options](PA5%20Options.md). 
- In this assignment, you will work with 1 other person. 
- There may be 1 group of 3 if there is an odd number of students in the section. 
- The group of 3 will have a larger amount of code to write, but the same amount of work per person.
- To view document (.docx), presentation (.pptx), or spreadsheet(.xlsx) files:
  - 🟠`Right-click on the file -> Open In -> Associated Application`🟠


## `FILE ORGANIZATION`

The files in this project are three major directories
- [Data files Directory](Data%20Files)
  - Contains the data files that you will be working on and extra md file specific to that problem
- [Supporting files Directory](Supporting%20Files)
  - Contains requirements, samples, check list as ([rubrics](Supporting%20Files/FEEDBACK.md)) and other supporting files
- [Working Files Directory](Working%20Files)
  - Files you will work on to complete your project
  - **<u>Copy the files specific to your project from *Data Files* to this folder</u>**
  
⛔️⛔️`Carefully examine each file for successful Completion of your project`⛔️⛔️

[⬆️⬆️⬆️Back To Top⬆️⬆️⬆️](#deadlines)

## `PURPOSE OF THE ASSIGNMENT`
* This assignment will give you practice with the vast majority of Python topics from this course. 
* It will also give you one last chance to show that you have learned how to pair program.
* This assignment gives you an opportunity to present your work to your classmates.

## `PARTNER AGREEMENT Submission`
Every group is required to fully fill out a partner agreement that includes information on how you plan to divide up the work, and when you plan to meet.
* You must assign a lead programmer to each function. 
  * This person is the driver on that function.
* Partners should be helping each other on all aspects of the program 
  * 🟠`Don't leave your partner hanging, or try to do their work for them. Support each other.`🟠
* You and your partner should divide the work evenly, ideally working in a pair programming style.
* Because this is a pair programming assignment, all programming must be done directly in replit. 

Partner agreement due at deadline above.
- You must fill out the provided form in `partner_agreement.md`:
  - 🟠`PUSH AND COMMIT AFTER SIGNING`🟠
- Your partner agreement as described above
- 🟠`I will tell you if your plan is OK or if you need to make changes. `🟠
- Be sure to read what you are agreeing to in the partner agreement document.

## `DESIGN Submission`

You must submit in your Github project by the design deadline:

* `initial_design.md`: 
  * A list of functions with function name, purpose, parameters (describe), and return value (describe).
    * 🔶`Add name of the driver for each function`🔶
  * The names here should match the names used in your partner agreement to list who will be lead programmer. 
  * It should be clear what part of the assignment each function represents.
* A `main.py` file with 
  * A code that properly reads from your input file, stores that information in an appropriate table (i.e. list of lists), 
  * A code that outputs the first and last 10 items of the table to the user so you can see that it works. 
  * User input of a filename should be fully implemented with error checking. 
    * No user input or output should occur in the file processing function.
  * 🔶`You should have 3 implemented functions at this point`🔶

[⬆️⬆️⬆️Back To Top⬆️⬆️⬆️](#deadlines)

## `ASSIGNMENT REMINDERS & WORKING AS A PAIR/GROUP`
* Follow the programming assignment requirements document for comments, formatting, etc. 
  * You will need to add function comments above each function in your code. 
* For each function in your PA you MUST list the author of that function in the function header comments. 
  * Be very clear about who was involved in each step.
* You will be required to fill out a survey privately about working with your partner 
  * ⏺️`You may NOT take this survey together or show your submission to your partner or any other student`.⏺️
  * I am expecting you to be honest. I may ask you for a meeting during finals week to discuss. 
  * If you are a very bad partner, you will not get full credit for the PA 
    * ⏺️`This includes both taking over the project and not letting your partner drive on their functions, and failing to fulfill your part of the project.`⏺️ 
    * You are expected to abide by the original partner agreement or an updated agreement if instructed by the professor to make a change.
* **The leader should be the person to write the code for their function.** 
  * Determine who is the leader for each function
* If you and your partner are having issues working together, talk to your instructor as soon as it becomes a problem. 
  * There is not much the instructor can do to help after the assignment is due or the night of the deadline.

## `USABILITY`

Follow good usability/HCI principles in designing your input and output. 
- Show that you've learned how to make great output and prompts! 
- It should be:
  - easy to understand how to use your program, 
  - easy to understand the output, and 
  - ❌`close to impossible to make your program crash!`❌

For output, unless your assignment specifies that something must be output to a file: 
- Use your discretion to determine if output to screen or file makes the most sense. 
- If it's too much output to read on screen, it probably needs to be in a file!

Graphs created by the program should be saved to a .jpg file. The user chooses the file name.

[⬆️⬆️⬆️Back To Top⬆️⬆️⬆️](#deadlines)

## `PROGRAMMING REQUIREMENTS`
After your design is complete, it’s time to start programming and then testing:

1. Implementation: Write your program following the below requirements and based on your design.
    * Practice iterative development: 
      * Instead of coding everything at once, code 1 part, get it to work right, then start the next part. 
    * For instance, code and test one question at a time.  
    * Look back at the steps given to you in recent labs.
    * Look at the code given in the class lecture note
2. Your program should work for ANY file of this format; 
   - ✅`if I gave you a new file of the same format, it should work without any changes.`✅
   * You should not assume the number of lines will be identical. 
   * Note how the files for your particular problem are delimited. 
3. Input: 
   - The user should provide names of input file, output file (if relevant), and plot files. 
   - User input should be error checked as makes sense for your particular problem.
4. Output: 
   - You must state the purpose of the program. 
   - You must make your output as clear as possible.  
5. Output Files: 
   - Be thoughtful about how you format output data in files. 
   - Do not simply put the result of a calculation without context. 
   - Do not output an entire list as one entity, you need to output each value separately.
6. Testing: `test_cases.txt`
   - Remember that creating a shorter test file with fewer lines may make it easier to double check the correct answer in Excel or by hand, to determine if your program seems to work correctly.
   - Does it store the data correctly? 
   - Does it calculate the answers correctly? 
   - ✅`Test it! I certainly will test it when I grade it.`✅
7. Expectations: 
   - ✅`You will use appropriate data structures including a dictionary.`✅ 
   - Your program will be efficient. 
   - For example, it should only read your file once, and will not create unnecessary duplicate lists.
8. Comments: 
   - In addition to the normal comments (line comments, function header comments, intro comments), 
   - ✅`Each function should list who was in charge of programming it.`✅ 
   - If both partners worked together in pair programming fashion, list both partners but also note who was driver.

[⬆️⬆️⬆️Back To Top⬆️⬆️⬆️](#deadlines)

## `FINAL PRESENTATION `

Students will present the results of their data analysis PA to the rest of the class. 
* Since each presentation is about different data, you will need to describe the data and the results
  * What did you learn about the data you analyzed? 
    * Don't just show values, interpret them. 
  * Beware that you don't introduce bias in your interpretation. 
* Details of the presentation format.
  * 🛑Look at `PA-Presentation Sample.pptx`🛑
* Your presentation grade will be based on:
  * the `content` of your presentation, 
  * the `style` of your presentation, and 
  * whether or not you p`ay attention and give feedback on your classmates’` presentations during the class period. 
* This part of your grade may be different between partners. 

**You must push and commit your group’s presentation file(s) to Github using `PA5 Presentation.pptx`. Use the Sample Presentation as a guidleing.**


## `Earning an E`
There are many opportunities to be creative and thoughtful when programming. 
- There is rarely one right way to solve a problem, although usually some approaches are better than others.  
- If I find that you have been particularly `creative (in a positive way) or thoughtful in any of the following manners`, that will help you earn an E (assuming the program meets requirements):

  1. Particularly well commented and organized code
  2. Particularly good/clear output, including excellent prompts
  3. Particularly excellent design, which includes great efficiency or data structure choices 
  4. Particularly well done presentation, as long as there is commenting in the code
  5. Particularly difficult student-designed question (that works)

[⬆️⬆️⬆️Back To Top⬆️⬆️⬆️](#deadlines)

## `What to Submit (Commit & Push) in GitHub`

Push each file according to the deadline in the table

1. Completed `main.py` file
2. Completed `initial_design.md` -> Contains the design of your program
3. Completed `findal_design.md` -> Contains the final design of your program
3. An Excel file with your test cases.  
    - Edit the `test_cases.xlsx` file with Excel software 
    - If it can open then ok. Otherwise
      - Right click on `test_cases.xlsx` -> Open In -> Associated Application
3. A presentation file for your project.  
    - Edit the `PA5-Presentation.pptx` file with Excel software 
    - If it can open then ok. Otherwise
      - Right click on `PA5-Presentation.pptx` -> Open In -> Associated Application
4. Encrypt your files using the `keys` and `process_reflection.py`
   1. `RD1.md` -> Reflection for Drive 1
   2. `RD2.md` -> Reflection for Drive 2
   3. If you use a different key, it is considered unsubmited
   - 🔴`Encrypting is a must`🔴 Ask a key if you lost the previous 
5. [The form rating your and your partners’ ability to work as a team.](https://forms.office.com/r/SxD7RAuWEi)
   - This is where you will reflect on the pair programming aspect of the assignment. 
   - 🔴`This is done at after the final submission on forms`🔴


**As a reminder, reflections count toward your participation grade.**

Type the Reflection INSIDE the respective markdown and addressing the following questions:

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

[⬆️⬆️⬆️Back To Top⬆️⬆️⬆️](#deadlines)
