<!--
ID: exercise-001
Tags: [python, beginner, programming, tutorial]
Description: A simple exercise to introduce basic Python programming concepts such as variables, data types, and user input.
Query: Give me a beginner-level getting started training exercise for python. Display the entire LLM output in a markdown formatted text string that I can copy or download. Make the exercise very positive and detailed. Include all prerequisites and steps. Add a hidden field to the top of the exercise with the following parameters: ID, Tags, Description, Query, Model, Level. Where ID is a unique ID. Where Tags is a list of tags associated with the exercise. Where Description is a short overview of the exercise. Where Query is this query string. Where model is the model and version of the LLM that I'm submitting the query to. Where level is the skill level of this exercise rated as beginner, intermediate, or advanced.
Model: ChatGPT-4
Level: beginner
-->

# Beginner Python Exercise: Getting Started with Basics

Welcome to your first Python exercise! This is a great opportunity to dive into the world of programming with Python. In this exercise, you will learn how to use basic Python features, including variables, data types, and user input. Let's get started!

## Prerequisites

Before starting this exercise, you should have:

1. **Python Installed**: Ensure Python is installed on your computer. You can download it from [python.org](https://www.python.org/downloads/).
2. **A Text Editor**: Use any text editor you prefer, such as VSCode, Sublime Text, or even Notepad.
3. **Basic Computer Skills**: Ability to navigate folders and run programs.

## Exercise Overview

In this exercise, you will:

1. Write a Python script that takes user input.
2. Perform some basic operations on the input.
3. Display the results to the user.

## Steps

1. **Create a New Python File**

   Open your text editor and create a new file named `first_program.py`.

2. **Write Your Script**

   Copy and paste the following Python code into `first_program.py`:

   ```python
   # A simple Python program to greet the user

   # Ask for the user's name
   name = input("What is your name? ")

   # Ask for the user's age
   age = input("How old are you? ")

   # Display a greeting message
   print(f"Hello, {name}! You are {age} years old.")
