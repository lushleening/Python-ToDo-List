# Python To-Do List (Jupyter Notebook)

A simple command-line based To-Do List application built using Python in a Jupyter Notebook.  
This project demonstrates basic programming concepts such as functions, loops, conditionals, exception handling, and list manipulation.

---

## Features

- Add new tasks with descriptions
- View all tasks with status (Pending / Done)
- Delete tasks
- Mark tasks as completed
- View only pending tasks
- Update existing tasks
- Input validation and error handling

---

## Core Functionalities

### 1. Add Task
- Users can add a task with a description
- Prevents empty task input

### 2. View Tasks
- Displays all tasks with:
  - Task name
  - Description
  - Status (Pending / Done)

### 3. Delete Task
- Allows users to remove a selected task
- Handles invalid inputs and out-of-range selections

### 4. Mark Task as Done
- Marks a task as completed
- Prevents marking already completed tasks

### 5. View Pending Tasks
- Shows only tasks that are not completed
- Handles cases where all tasks are completed or no tasks exist

### 6. Update Task
- Allows modification of task name and description
- Prevents empty task updates

---

## How to Run

1. Clone the repository:
```bash
git clone https://github.com/your-username/your-repo-name.git
```

2. Open Jupyter Notebook:
```bash
jupyter notebook
```

3. Open the notebook file:
```text
todolist.ipynb
```

4. Run all cells and use the interactive menu.

---

## Edge Cases Handled

- Empty task input is rejected
- Invalid menu selections are handled
- Non-numeric input is handled safely
- Out-of-range task selections are prevented
- Empty task list scenarios are handled gracefully
- Prevents marking already completed tasks
- Handles fully completed task states correctly

---

## Project Summary

This project is a menu-driven console application that allows users to manage a personal task list. It demonstrates the use of structured programming, user input validation, and list-based data management in Python.
