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
- [Solutions To Previous Labs and PAs](https://classroom.github.com/classrooms/193636664-sp25-zjy-cs212)

- **You can use LLM (Such as ChatGPT or Gemini) as a guider but not as a problem Solver**  
  🟠**LLM-Based Codes Will Result in Penalty and Honor Code Violation**🟠

- ⚠️ **To edit the flow chart file, add `diagrams.net` plugin** ⚠️
    - File -> Settings -> Plugins -> Marketplace: Then search and install `diagrams.net`.
    - Update the flowchart of your project using [`Flow Chart`](uml.drawio.svg).

---

## `III. PROBLEM`
You have probably done CS 151. **🟡 What's Old is New Again 🟡**
- If you have not, don't worry; it should not impact your ability to finish the assignment.
- If you have done this assignment in CS 151, you will need to come up with another adventure story.

You are creating a text-based choose-your-own-adventure game! In this game:
- The user provides input that affects the path of the story.
- Your game must meet the requirements outlined in the specifications below.

---

## `IV. PURPOSE OF THE ASSIGNMENT`
The purpose of this assignment is to give you:

1. A chance to code in Java.
2. Practice with input & output.
3. An opportunity to use branching.
4. A chance to be creative.

[<h2>⬆ Back To Top ⬆</h2>](#i-deadlines)

---

## `V. REQUIREMENTS ANALYSIS`
The first stage of your programming assignment is the **requirements analysis**. Ensure you understand the following:

1. Your adventure game must ask the user at least one question for each of the following:
    - An **integer input**.
    - A **float/double input**.
    - A **string input**.
2. Your adventure game must:
    - Have a path with **at least 2 decisions**.
    - Include a decision with **3 or more possible directions**.
    - Use **3 different boolean operators**.
    - Provide **specific inputs** for at least one decision (e.g., "enter 'red', 'green', or 'blue'").
    - Use user input in the output at least once (e.g., addressing the player by their name).
3. Assume users will input correct data types.
4. **Extra credit** 🟢 5 points: Use a loop to ask the user if they want to replay the game after it ends.

**⚠️ The game must be logical and have an understandable story. Your professor will read the entire story. ⚠️**



---

## `VI. DESIGN`
The second stage is to design your solution based on the requirements:

1. Write out your algorithm, including:
    - Input, output, decisions, and calculations.
    - Proper indentation and numbering to indicate nested decisions.
2. Label reusable story elements (e.g., "story part 1") to reference them as needed.
3. Double-check that all requirements are included.

**💡 Inspiration**: Use books or movies you enjoy to create an original story.  

---

## `VII. PROGRAMMING REQUIREMENTS`
After completing your design, follow these steps:

1. **Fix design issues**: Ensure your design meets all requirements.
2. **Implementation**: Write your program based on the design.
    - Use meaningful prompts for inputs.
    - Clearly state the program's purpose in comments.
3. **Testing**:
    - Create a flowchart of control paths with test cases.
    - Test every control path and document the results.

**⛔️ Testing Tip**: Your flowchart should make each path clear.

[<h2>⬆ Back To Top ⬆</h2>](#i-deadlines)

---

## `VI. STYLE`
Follow these style guidelines:

1. **File headers**: Include at the top of each file:
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

2. **Variable names**: Use meaningful camelCase names.
3. **Code formatting**: Use consistent indentation, whitespace, and alignment.
4. **Documentation**: Add comments for clarity.
5. **Git usage**: Commit after milestones with meaningful messages. Avoid a single commit for the entire project.


## `IX. SUBMISSIONS`

### `DESIGN SUBMISSION: Sunday 01/20 11:59PM`
**🔶 Commit and Push to GitHub: 🔶**

1. Submit the following:
    - [`initial_design.md`](initial_design.md): Your initial algorithm.
    - [`flowchart.drawio.svg`](uml.drawio.svg): Flowchart in SVG format.
    - **If using another program**: Export the flowchart to PDF format before submission.
    - **If hand-drawn**: Scan or photograph the flowchart, convert it to PDF, and upload it.

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
    - [`flowchart.drawio.svg`](uml.drawio.svg): Final flowchart of your program.
    - [`reflection.md`](reflection.md): Reflection document addressing the questions below.

2. Ensure all files are:
    - **Correctly named** and placed in your project folder.
    - **Pushed to GitHub** and verified on `github.com`.
    - Use **meaningful commit messages** for each milestone.
---

[<h2>⬆ Back To Top ⬆</h2>](#i-deadlines)