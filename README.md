# Pomodoro Timer App

This project is a simple **Pomodoro Timer** application built with **Python** and **Tkinter**. The Pomodoro Technique is a time management method that uses a timer to break work into intervals, traditionally 25 minutes in length, separated by short breaks. This app automates that process, helping to boost productivity and focus.

## Features

- **Timer Cycles**: Automatically switches between work sessions, short breaks, and long breaks.
- **UI Design**: Includes a custom UI with a tomato image as the timer's visual representation.
- **Progress Tracking**: Displays checkmarks for completed work sessions.

## Languages and Libraries Used

- **Python**: The primary programming language used to create the logic of the timer and the UI.
- **Tkinter**: A built-in Python library used to create the graphical user interface (GUI).
- **Math**: The standard `math` library is used for rounding and formatting timer values.

## How It Works

1. **Start Button**: Click to start the Pomodoro cycle. The timer will count down 25 minutes for work, followed by a 5-minute short break. After every 4 work sessions, a longer 20-minute break is triggered.
2. **Reset Button**: Resets the timer and progress.
3. **UI**: A tomato image represents the timer, and a label keeps track of the remaining time. After each work session, a checkmark is added to indicate progress.
