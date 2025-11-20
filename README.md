========================================
TASK MANAGEMENT SYSTEM (TMS) README
========================================

## 1. Overview

The Task Management System (TMS) is a streamlined, command-line (or basic interface) application designed to help users efficiently manage their daily tasks. It allows users to quickly add new tasks, modify existing entries, and delete completed or irrelevant tasks, providing a simple yet powerful tool for personal or small-team productivity.

## 2. Key Features

The TMS is built around three core functionalities:

* **Add Task:** Create a new task entry with a description and optional details (like priority or due date).
* **Edit Task:** Modify the details or status of any existing task.
* **Delete Task:** Permanently remove a task from the system.

## 3. Getting Started

### 3.1. Prerequisites

(If this were a real application, list the necessary requirements here, e.g.)
* Python 3.x
* (Any specific libraries, e.g., 'sqlite3' if using a database)

### 3.2. Installation

(If this were a real application, provide installation instructions, e.g.)
1.  Download the source code archive from the repository.
2.  Extract the files to your desired directory.
3.  Install dependencies: `pip install -r requirements.txt`
4.  Run the application: `python run_tms.py`

## 4. Usage Instructions

The system operates via a menu-driven interface. Upon launch, you will see a list of available commands.

### 4.1. Main Menu Commands

| Command | Description | Example Input |
| :---: | :--- | :--- |
| `list` | Displays all current tasks with their IDs and status. | `list` |
| `add` | Prompts you to enter a new task description. | `add` |
| `edit` | Prompts for a Task ID to modify its details. | `edit` |
| `delete` | Prompts for a Task ID to permanently remove the task. | `delete` |
| `help` | Displays this help/command list. | `help` |
| `exit` | Closes the Task Management System. | `exit` |

### 4.2. Adding a Task (`add`)

1.  Enter `add` at the command prompt.
2.  Follow the prompts to enter the task description (e.g., "Finish README file
