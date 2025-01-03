### **Project Title**: **"Simple Task Manager"**

---

### **Objective**:
Create a Bash script to manage a list of tasks. Users can add, view, complete, and delete tasks stored in a plain text file.

---

### **Steps and Guide**:

#### **1. Initialize the Script**:
- Start by creating a script file (e.g., `task_manager.sh`).
- Add a shebang (`#!/bin/bash`) at the top.

---

#### **2. Set Up a Storage File**:
- Define a file (e.g., `tasks.txt`) to store tasks.
- Check if the file exists when the script starts. If it doesn’t, create it.

---

#### **3. Display a Menu**:
- Create a menu with options such as:
  - Add a new task.
  - View all tasks.
  - Mark a task as completed.
  - Delete a task.
  - Exit the script.

---

#### **4. Implement Add Task**:
- Prompt the user to enter a task description.
- Append the task to the `tasks.txt` file, along with a status (e.g., "Pending").

---

#### **5. Implement View Tasks**:
- Read and display all tasks from the file.
- Show task numbers, descriptions, and their statuses (e.g., "Pending" or "Completed").

---

#### **6. Mark a Task as Completed**:
- Display the list of tasks with numbers.
- Prompt the user to select a task by its number.
- Update the selected task's status in the file to "Completed".

---

#### **7. Delete a Task**:
- Display the list of tasks with numbers.
- Prompt the user to select a task by its number.
- Remove the selected task from the file.

---

#### **8. Handle Invalid Inputs**:
- Ensure that inputs are validated (e.g., numbers for task selection).
- Display appropriate error messages for invalid inputs.

---

#### **9. Loop Until Exit**:
- Use a loop to keep showing the menu until the user chooses the "Exit" option.

---

### **Bonus Features**:
- Allow the user to set due dates for tasks.
- Add a search feature to find tasks by keyword.
- Color-code tasks (e.g., pending tasks in yellow, completed tasks in green) for better readability using `tput`.
