# Introduction to Computer Science - Fall 2017

## Lab 5 - Variables, user Interaction, and Arithmetic

**Purpose:** The purpose of this lab is to introduce arithmetic to JavaScript and user interaction. You will get some experience developing interactive Web pages using both HTML and JavaScript. You will design and write a simple page that computes the weighted average of scores in a typical college course.

**Practice:** Study the [Interactive JavaScript](http://itech190.erickuha.com/) demos. Pay attention especially to the two versions of the tip calculator.

**Instructions:** Create a Web page called _grades.html_ that serves as an interactive wegithed-average calculator. The page should start out with a brief description of what the page does and what the user should do to use the page. It should include a table (using a `<table>` element) that lists the following information:

* Homework is worth 25% of the final grade
* Labs are worth 20% of the final grade
* The Midterm Exam is worth 25% of the final grade
* The Final Exam is worth 30% of the final grade

The next part of the page should include four text boxes that will allow a user to enter their scores for each of the four graded items: Homework, Labs, the Midterm Exam, and the Final Exam. Note that you can assume that the scores they enter are out of 100.

You should have a button that will calculate the weighted average for the person. Then the average, along with a descriptive message, should be displayed in the division element (div) on the same page. For example, if the person entered 92, 86, 95, 88, the calculation would be:

`average = 92 * 0.25 + 86 * 0.20 + 95 * 0.25 + 88 * 0.30`

The output should be something like:

`Your weighted average is 90.35`

note that your page must contain the following:

* It must have a table (no borders are necessary) with two columns where the left column is right-aligned and the right column is left-aligned.
* The JavaScript must use at least four variables.
* There must be at least one arithmetic expression using variables
* The resulting average must appear in its own `<div>` element that gets updated by JavaScript after the user clicks the button.
* Be sure that you **test** your program. At the very least, it should give the response that is in the example above. In addition, you should create your own set of inputs. Use a calculator to determine the correct output and then verify that your program gives the same results.

Once you have completed the assignment, push it back to your repository for grading.
