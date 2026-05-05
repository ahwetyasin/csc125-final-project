# csc125-final-project
“My Python final project for CSC-125-201
-Welcome to my Final Project
# CSC-125-201 Final Project
# Project Description
My program is called the Workout Logger. It is a simple text based program where you can keep track of your exercises.
# Features

-I use a dictionary called workout_log. The keys are exercise names that the user types in, like "squat" or "bench press". Each value is another small dictionary with "sets" and "reps" as integers. So it ends up looking something like workout_log["squat"] = {"sets": 3, "reps": 10}. The program reads from it when showing the summary and adds to it every time the user logs something.

-I have a function called display_summary. It takes workout_log as a parameter. Inside it loops through the dictionary and prints each exercise with its sets and reps. At the end it returns the total number of exercises logged, so the main program can print that count to the user.

-The main loop is a while loop. It keeps going until the user types "quit". Each time through, it shows the menu and waits for a command. When the user types "quit" it breaks out and the program ends. So the user can log as many exercises as they want before stopping.

-The program asks for four things: a menu command ("log", "summary", or "quit"), an exercise name, the number of sets and the number of reps. All of them use input() and get stored in variables.

-The program prints a welcome message at the start. Then at each loop it shows the menu. After logging an exercise it confirms it worked. The summary shows all exercises with sets and reps. When you quit it also shows the total count.

# Status
In progress. Pseudocode design is in this repo.
Final .ipynb will be uploaded after May 15, 2026.
# Course
CSC-125-201, Spring 2026, Bunker Hill Community College
