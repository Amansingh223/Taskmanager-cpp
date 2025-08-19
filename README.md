# 🗂️ Task Manager (C++)

A **console-based Task Manager application** built in **C++**.  
It allows users to add, delete, and view tasks while storing them persistently in a file.  
The project demonstrates **OOP, STL containers, file handling, and the Singleton Design Pattern**.

---

## 🚀 Features
- Add new tasks with **title, description, and due date**
- Delete a task by its title
- View all tasks in a clean format
- Persistent storage using a text file (`mytasks.txt`)
- Ensures **only one TaskManager instance** using the Singleton Pattern

---

## 🛠️ Tech Stack
- **Language:** C++ (C++11/14/17 compatible)
- **Concepts Used:**
  - Classes & Encapsulation
  - Forward List (`std::forward_list`)
  - File Handling (save/load tasks)
  - Singleton Design Pattern
  - Console-based interaction

---

---

## ⚡ How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/YourUsername/cpp-task-manager.git
   cd cpp-task-manager

   
Compile the project:
g++ main.cpp -o taskmanager
Run the program:
./taskmanager


## 📂 Project Structure
TaskManager/
│── main.cpp # Main program (Task Manager implementation)
│── mytasks.txt # Stores all saved tasks
│── README.md # Project documentation


====== Task Manager ======
1. Add New Task
2. Delete Task
3. View All Tasks
4. Exit
Enter your choice: 1

Enter task title:
Complete Assignment
Enter task description:
Finish the pending math assignment
Enter due date:
20-08-2025
Task Added Successfully
