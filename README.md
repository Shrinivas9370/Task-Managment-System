## 1. Overview

The Task Management System (TMS) is a simple command-line application that helps users manage their daily tasks efficiently. Users can quickly add new tasks, change existing ones, and delete completed or unnecessary tasks. This tool is effective for individual or small team productivity.

## 2. Key Features

The TMS focuses on three main functions:

* **Add Task:** Create a new task entry with a description and optional details, such as priority or due date.
* **Edit Task:** Change the details or status of an existing task.
* **Delete Task:** Permanently remove a task from the system.

## 3. Getting Started

### 3.1. Prerequisites

* Python 3.x
* (Any specific libraries, e.g., 'sqlite3' if using a database)

### 3.2. Installation

1. Download the source code archive from the repository.
2. Extract the files to your preferred directory.
3. Install dependencies: `pip install -r requirements.txt`
4. Run the application: `python run_tms.py`

## 4. Usage Instructions

The system works through a menu-driven interface. When you launch it, you will see a list of available commands.

### 4.1. Main Menu Commands

| Command | Description | Example Input |
| :---: | :--- | :--- |
| `list` | Displays all current tasks with their IDs and status. | `list` |
| `add` | Prompts you to enter a new task description. | `add` |
| `edit` | Asks for a Task ID to change its details. | `edit` |
| `delete` | Asks for a Task ID to permanently remove the task. | `delete` |
| `help` | Shows this help/command list. | `help` |
| `exit` | Closes the Task Management System. | `exit` |

### 4.2. Adding a Task (`add`)

1. Enter `add` at the command prompt.
2. Follow the prompts to enter the task description (e.g., "Finish README file").
