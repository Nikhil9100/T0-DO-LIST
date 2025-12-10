# 📝 C++ Console To-Do List Application

A simple and beginner-friendly **To-Do List application** built using **C++**.  
This project demonstrates the use of **vectors, functions, string handling, file handling**, and basic console-based UI.

---

## 🚀 Features

- ➕ Add new tasks  
- ✔️ Mark tasks as complete  
- ❌ Delete tasks  
- 📃 View all tasks with status  
- 💾 Auto-save tasks to a text file (`tasks.txt`)  
- 📂 Load saved tasks when the program starts  

---

## 🛠️ Technologies Used

- C++ (Standard Template Library)
- File Handling (fstream)
- Vectors for dynamic storage

---

## 📌 How It Works

The application stores all tasks in a **vector** of `Task` objects.  
Each task has:
- `desc` – description of the task  
- `done` – completion status  

Tasks are saved to `tasks.txt` so your list persists even after exiting the program.

---

## 🧩 Code Snippet

```cpp
vector<Task> tasks;

void add_task() {
    string desc;
    getline(cin, desc);
    tasks.push_back({desc, false});
}


🔧 How to Run

Clone the repository:

git clone https://github.com/Nikhil9100/T0-DO-LIST.git


Navigate into the folder:

cd T0-DO-LIST


Compile the program:

g++ -std=c++17 todo.cpp -o todo


Run:

./todo


📚 Learning Objectives

Understand basic C++ syntax

Learn how vectors work

Use functions for modular design

Implement file handling for data persistence

Build a complete console-based mini project



🌟 Future Enhancements

Add task priority

Add due dates

Add categories/tags

Export tasks to JSON/CSV

Convert into GUI app using Qt or GTK

🙌 Contributor

Nikhil
B.Tech Student | Data Science | Developer

📜 License

This project is open-source and available under the MIT License.


---

If you want, I can also:

✅ Add badges  
✅ Add screenshots  
✅ Format it with emojis or a professional style  
✅ Match README design to your LinkedIn style  

Just tell me!
