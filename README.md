 Task-Tracker-CLI
A CLI Program to manage task

Add a Task: Add a new task with a description.
Update a Task: Update the description of an existing task.
Delete a Task: Remove a task by its ID.
Mark a Task: Mark a task as "in progress" or "done."
List Tasks: List all tasks or filter them by status (e.g., todo, in progress, done)

1. Compile :
javac TaskCLIApp.java Task.java TaskManager.java Status.java

2. Then go to the out/targter-classes 
and run below:

Adding a new task
java TaskCLI add "Buy groceries"
Output: Task added successfully (ID: 1)

 Updating a task
java TaskCLI update 1 "Buy groceries and cook dinner"
 Output: Task updated successfully (ID: 1)

 Deleting a task
java TaskCLI delete 1
Output: Task deleted successfully (ID: 1)

 Marking a task as in progress
java TaskCLI mark-in-progress 1
 Output: Task marked as in progress (ID: 1)

 Marking a task as done
java TaskCLI mark-done 1
 Output: Task marked as done (ID: 1)

 Listing all tasks
java TaskCLI list
 Output: List of all tasks

 Listing tasks by status
java TaskCLI list todo
java TaskCLI list in-progress
java TaskCLI list done
