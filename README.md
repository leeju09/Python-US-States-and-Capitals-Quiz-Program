# U.S. States and Capitals Quiz Program

An interactive Python quiz program that tests users' knowledge of U.S. state capitals.
The program randomly selects 5 states per session, validates user input, tracks scores, and provides encouraging feedback based on performance.

## Overview

This program was built as part of **DSCI 2001-51: Data Science I**. It demonstrates core Python skills including dictionaries, the 'random' module, user input handling, string normalization, and function decomposition.

## Features

- **Complete 50-state dictionary** — every U.S. state mapped to its capital
- **Random selection with no repeats** — uses `random.sample()` to pick 5 unique states per session
- **Case-insensitive matching** — "austin", "Austin", and "AUSTIN" all count as correct
- **Smart spelling tolerance** — handles variations like "St. Paul", "St Paul", and "Saint Paul"
- **Input validation** — re-prompts the user if they submit an empty answer
- **Live feedback** — immediate "Correct!" or "Incorrect. The answer is ..." after each question
- **Progress display** — shows "Question X of 5" during the quiz
- **Score-based encouragement** — different messages for 5/5, 4/5, 3/5, 1–2/5, and 0/5

## How to Run

1. Open `python_ds_assignment_us_capitals_quiz_JuliaLee.ipynb` in Google Colab
2. Click **Runtime → Run all**
3. When the quiz cell pauses for input, type your answer and press **Enter**
4. Repeat for all 5 questions

No external libraries are required — only the built-in `random` module.

