# To Do saraksts

A lightweight desktop to-do list application built with Python and CustomTkinter.  
It helps users manage tasks in a weekly Kanban-style workflow and persists data locally in a JSON file.

## Overview

This project is a simple personal task manager with:

- a weekly board for organizing tasks by state
- a full task list for sorting and management
- automatic saving to `tasks.json`
- a modern desktop interface

The app supports three task states:

- Jāsāk
- Daru
- Pabeidzu

## Features

- Add new tasks with:
  - title
  - priority
  - deadline
- Mark tasks as included in the weekly plan
- Move tasks between workflow stages
- Sort all tasks by:
  - alphabetical order
  - priority
  - status
- Delete tasks from the list
- Keep tasks saved automatically between sessions

## Project Structure

```text
To-Do-saraksts/
├── main.py
├── models.py
├── tasks.json
├── ui/
│   ├── add_task_dialog.py
│   ├── all_tasks_view.py
│   └── weekly_view.py
├── idea/
└── README.md