# Sprint Challenge: JavaScript Fundamentals

This challenge allows you to practice the concepts and techniques learned over the past week and apply them in a survey of problems. This Sprint explored JavaScript Fundamentals. During this Sprint, you studied variables, functions, object literals, arrays, this keyword, prototypes, and class syntax. In your challenge this week, you will demonstrate proficiency by completing a survey of JavaScript problems.

## Instructions

**Read these instructions carefully. Understand exactly what is expected _before_ starting this Sprint Challenge.**

This is an individual assessment. All work must be your own. Your challenge score is a measure of your ability to work independently using the material covered through this sprint. You need to demonstrate proficiency in the concepts and objectives introduced and practiced in preceding days.

You are not allowed to collaborate during the Sprint Challenge. However, you are encouraged to follow the twenty-minute rule and seek support from your PM and Instructor in your cohort help channel on Slack. Your work reflects your proficiency in JavaScript fundamentals.

You have three hours to complete this challenge. Plan your time accordingly.

## Commits

Commit your code regularly and meaningfully. This helps both you (in case you ever need to return to old code for any number of reasons) and your project manager.

## Description

You will notice there are several JavaScript files being brought into the index.html file.  Each of those files contain JavaScript problems you need to solve.  If you get stuck on something, skip over it and come back to it later.

In meeting the minimum viable product (MVP) specifications listed below, you should have a console full of correct responses to the problems given.

## Self-Study Questions

#################################### COMPLETED #######################################

Demonstrate your understanding of this week's concepts by answering the following free-form questions.

Edit this document to include your answers after each question. Make sure to leave a blank line above and below your answer so it is clear and easy to read by your project manager

1. Describe the biggest difference between `.forEach` & `.map`.

`.forEach` and `.map` are both used to manipulate every value inside of an array, but `.forEach` always returns `undefined` while `.map` returns another array with the changed values. `.forEach` is very useful for manipulating array values and logging them to the console for example, while `.map` is very useful for changing array values and then accessing the changed values for another purpose. 

2. What is the difference between a function and a method?

A function is a section of code that takes a parameter or input value, manipulates that value in some way, and then (most likely) returns some data. A method is essentially a function that is tied to an object. A method can access properties of that object (using the `this` keyword), and manipulate that data in some way. In addition, in order to use a method, it must be called using the object. For example: `Object.method()`

3. What is closure?

Closure means that a function that is nested inside of another function has access to that outer function's variables. When attempting to access a variable, the function will first look for that variable in its own scope, and if it can't find it, it will look outwards until it finds the variable.

4. Describe the four rules of the 'this' keyword.

The `this` keyword has four rules in which it can be used: window binding, implicit binding, new binding, and explicit binding. Window binding means that when in the global / window scope, the "this" keyword refers to the window object. Implicit binding means that when inside of a local scope (an object), the "this" keyword refers to the object in which the "this" keyword is located. New binding means that when an object is created from a constructor function / class, the "this" keyword refers to the object that is created using the constructor function or class. Explicit binding means that when the "call" and "apply" methods are used, the "this" keyword refers to whatever is explicitly defined inside of the method.

5. Why do we need super() in an extended class?

We need to use `super()` in an extended class because it essentially tells the extended class that it should inherit the properties from the parent class. The extended class then has access to the properties of the parent, and can also be assigned its own specific properties.

## Project Set up

Follow these steps to set up and work on your project:

- [ ] Create a forked copy of this project.
- [ ] Add PM as collaborator on Github.
- [ ] Clone your OWN version of Repo (Not Lambda's by mistake!).
- [ ] Create a new Branch on the clone: git checkout -b `<firstName-lastName>`.
- [ ] Create a pull request before you start working on the project requirements.  You will continuously push your updates throughout the project.
- [ ] You are now ready to build this project with your preferred IDE
- [ ] Implement the project on your Branch, committing changes regularly.
- [ ] Push commits: git push origin `<firstName-lastName>`.

Follow these steps for completing your project:

- [ ] Submit a Pull-Request to merge <firstName-lastName> Branch into master (student's  Repo).
- [ ] Add your Project Manager as a Reviewer on the Pull-request
- [ ] PM then will count the HW as done by  merging the branch back into master.


## Minimum Viable Product

Your finished project must include all of the following requirements:

**Pro tip for this challenge: If something seems like it isn't working locally, copy and paste your code up to codepen and take another look at the console.**

## Task 1: Objects and Arrays
Test your knowledge of objects and arrays. 
* [ ] Use the [objects-arrays.js](challenges/objects-arrays.js) link to get started.  Read the instructions carefully!

#################################### COMPLETED #######################################

## Task 2: Functions
This challenge takes a look at callbacks and closures as well as scope. 
* [ ] Use the [functions.js](challenges/functions.js) link to get started. Read the instructions carefully!

#################################### COMPLETED #######################################

## Task 3: Prototypes
Create constructors, bind methods, and create cuboids in this prototypes challenge.
* [ ] Use the [prototypes.js](challenges/prototypes.js) link to get started. Read the instructions carefully!

#################################### COMPLETED #######################################

## Task 4: Classes
Once you have completed the prototypes challenge, it's time to convert all your hard work into classes.
* [ ] Use the [classes.js](challenges/classes.js) link to get started. Read the instructions carefully!

#################################### COMPLETED #######################################

In your solutions, it is essential that you follow best practices and produce clean and professional results. Schedule time to review, refine, and assess your work and perform basic professional polishing including spell-checking and grammar-checking on your work. It is better to submit a challenge that meets MVP than one that attempts too much and does not.

## Stretch Problems

There are a few stretch problems found throughout the files, don't work on them until you are finished with MVP requirements!

#################################### COMPLETED #######################################
