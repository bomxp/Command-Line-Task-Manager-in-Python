
# Command-Line Task Manager in Python

This is a simple command-line application that helps users manage their daily tasks. The program supports adding, viewing, completing, and deleting tasks using a menu-based interface.

## Features

- Add a new task with a description
- View all current tasks and their status (Pending/Done)
- Mark a task as completed using its ID
- Delete a task by its ID
- Input validation for task descriptions and task IDs

## How to Run

1. Make sure you have Python 3.x installed.
2. Download the file `task_manager_validated_commented.py`.
3. Run the script from your terminal or command line:

```bash
python task_manager_validated_commented.py
```

4. Follow the on-screen options: `add`, `view`, `complete`, `delete`, `exit`.

## Approach

The application uses:
- A list of dictionaries to store task data
- Functions for modular and reusable code
- A loop-based CLI for continuous interaction

### Data Structure

```python
{
    "id": int,              # Unique task ID
    "description": str,     # Task description
    "completed": bool       # Completion status
}
```

## Challenges & Solutions

- **Input validation**: Prevented empty descriptions and ensured task IDs are numeric.
- **Task ID management**: Automatically assigned incrementing IDs using list indexing.

## Optional Enhancements (not implemented)

- Persistent storage using file (JSON/CSV)
- Task editing/updating
- Due dates and priorities

