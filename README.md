# PythonProject2_TODO_LIST_CLI
A Python command-line to-do list application showcasing procedural programming and OOP concepts using instance, static, and class methods

📝 Python To-Do List (CLI)

This project demonstrates how to build a To-Do List Command-Line Application in Python, while progressively applying Object-Oriented Programming (OOP) concepts.

The project is split across four Jupyter notebooks, each introducing a new programming style or OOP feature:

📂 Files Overview
1. PythonProgramming_PythonProject2_TO-DO_LIST(CLI).ipynb

Implements the basic To-Do List CLI using a procedural approach.

Features:

Add tasks

View tasks

Delete tasks

Exit option

Uses functions and a global list (todo_list) to manage tasks.

2. PythonProgramming_Pythonproject2_TO-DO_LIST(CLI)_ImplementingOOPsConcept.ipynb

Refactors the procedural code into OOP (Object-Oriented Programming).

Features:

ToDoList class with methods:

show_tasks()

add_task()

delete_task()

Encapsulation: tasks are stored inside self.tasks.

The program runs using an object instance of the class.

3. PythonProgramming_PythonProject2_TO-DO_LIST(CLI)_ImplementingOOPsConcept_usingStaticMethod.ipynb

Demonstrates the use of @staticmethod.

Features:

tasks is a class-level list (shared across all static methods).

All methods (show_tasks, add_task, delete_task, menu) are static.

The program runs without creating any object; methods are called directly via the class.

4. PythonProgramming_PythonProject2_TO-DO_LIST(CLI)_ImplementingOOPsConcept_usingClassMethod.ipynb

Demonstrates the use of @classmethod.

Features:

todo_list is a class variable.

Methods (show_tasks, add_task, delete_task) are defined as class methods, using cls to access class data.

Provides flexibility for subclassing and extending behavior.

🚀 Key Learning Outcomes

Transition from procedural programming → OOP with instances → Static Methods → Class Methods.

Understanding:

Instance Methods (operate on object’s data)

Static Methods (utility methods, no object needed)

Class Methods (operate on class-level data, support inheritance)

▶️ How to Run

Open any .ipynb file in Jupyter Notebook or VS Code (with Python extension).

Run the cells step by step.

Follow the CLI prompts to add, view, or delete tasks.
