## Task Manager

The Task Manager is a Python program that allows users to manage tasks effectively. It provides functionalities to add tasks, remove tasks, and display tasks.

### Features

- Add tasks: Users can add new tasks with a unique task ID, description, and status.
- Remove tasks: Users can remove tasks based on their task ID.
- Display tasks: Users can view all the tasks currently in the task list.

### How to Use

1. Create instances of the `Task` class with task details such as task ID, description, and status.
2. Add tasks to the `TaskManager` object using the `add_task` method.
3. Display all tasks using the `display_tasks` method.
4. Remove tasks using the `remove_task` method based on their task ID.

### Example

```python
# Initialize TaskManager
task_manager = TaskManager()

# Sample tasks
task1 = Task(1, "Complete assignment", "Pending")
task2 = Task(2, "Attend meeting", "In Progress")
task3 = Task(3, "Submit report", "Completed")

# Add tasks to the task manager
task_manager.add_task(task1)
task_manager.add_task(task2)
task_manager.add_task(task3)

# Display tasks
task_manager.display_tasks()

# Remove task
task_manager.remove_task(2)

# Display tasks after removal
task_manager.display_tasks()

```

### Contributing

Contributions to improve the Task Manager project are welcome! Fork the repository, make your changes, and submit a pull request.

### Credits

This project was created by Jeel patel
