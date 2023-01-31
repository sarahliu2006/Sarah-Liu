---
toc: true
title: Week 20 CPT Outline 
layout: post
description: CPT Outline
permalink: /cptoutline
categories: [markdown,week20,tri2]
tags: true
---

# Program Purpose and Function
In my video, I will demonstrate filling out the multiple choice questionnaire (input). Once I hit submit, it will show the output, which will be the model name (and possibly an image) of the best fit chevrolet car for the user.

Written Response:

Function: A questionnarie on a website which recommends a chevrolet vehicle that would best match with a user's transportational needs

Purpose: To help people who are trying to buy a new car find the chevrolet car model which best meets their needs. This helps people save time when they're trying to buy a new car, and also to be prepared when they visit the dealership.

Input: user answering car search tool questionnaire on frontend

Output: car recommendation

# Data Abstraction
Code segment which shows that data is being stored in a list: create array with quiz questions and iterate through them

Code segment which shows the data in the same list being used as a part of fulfilling the program's purpose: loop through questions --> if user's answer marches with a product's assigned answer --> add one point to that car model, just like a quiz assigning points to a student

Identify name of variable representing list being used: TBD

Describes what the data contained in this list is representing in the program: the data contained in the list will be the questions that the users will be asked and the answer sets that go along with them to determine which chevrolet car recommendation they'll get

# Managing Complexity
Explains how the list manages complexity, how the program would be different without the use of the list, and why I need it for my program: If I use a list to store the data for questions and the user's answers, it will be easier for the program to come up with a result for the car recommendation by adding up points for each car and then choosing the car which is the best fit for them
Procedural Abstraction
Code segment that shows a student-developed procedure with at least one parameter that has an effect on the functionality of the procedure: Create function that adds points to the cars which match with the user's input --> whichever car has the most points will be printed as the best fit match --> works like a graded quiz, kind of

Show a code segment where the student-develop procedure is being called: show a place where my quiz point adder will be called

Describes what the identified procedure does and how it contributes to the overall functionality of the program: The procedure essentially finds the car in the list which is the best match for the user. Without the procedure, the program would not be able to find a best fit car for the user

# Algorithm Implementation
Code segment in student-developed procedure shows sequencing, iteration, and selection

Explain in detail steps how the identified algorithm works in enough detail that someone else could recreate it: explain each step of the algorithm

# Testing
One call to program

Question: "What type of car do you prefer"
User Input: "Sedan"
Condition: If loop, if user chooses "sedan," add one point to all the variables for cars which are sedans
Output: The car which is outputted will be a sedan
Second call to program

Question: "What power source do you prefer"
User Input: "Hybrid"
Condition: If loop, if user chooses "hybrid," add one point to all the variables for cars which are hybrid
Output: The car which is outputted will be a hybrid sedan, using both of these calls to come up with the final result