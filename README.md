# DenInternship_week2
----------------------------------------------------

# 📋 My Tasks – Personal Task Manager App

Internship Task 2
This Android application helps users manage their daily tasks efficiently with features like task creation, editing, marking as done, category tagging, and more. Built using Java, XML, Room DB, and MVVM architecture

---

## 🚀 Features

### ✅ Core Functionalities

* **Add New Task**

  * Includes: Title, Description, Due Date, Priority (High/Medium/Low), Category (e.g., Work, School, Personal)
* **View Tasks**

  * Tasks are displayed in a **RecyclerView** using custom cards
  * Tasks sorted by priority and date
* **Edit & Update Task**

  * Tap the ✎ Edit icon to update task information
* **Delete Task**

  * 🗑️ Icon to remove tasks with instant update
* **Mark as Completed**

  * Checkbox to mark tasks as completed/incomplete
  * Completed tasks are shown with strikethrough text

### 📂 Task Categorization

* Tasks can be categorized under predefined tags like:

  * **Work**, **Personal**, **School**, etc.
* Helps with visual organization and filtering

---

## 🧑‍💻 Technical Highlights

* **Language & Tools:** Java, Android Studio, XML
* **Architecture:** MVVM
* **Database:** Room Database for local storage
* **UI Components:** RecyclerView, CardView, Buttons, CheckBox
* **Live Updates:** LiveData observers for reactive UI updates
* **Navigation:** Between task list, add/edit screen, and task detail view
* **Date Handling:** Custom logic for days remaining and overdue tasks with color indicators

## 🧭 Navigation Flow


MainActivity (Task List)
       ↳ AddTaskActivity
       ↳ EditTaskActivity
       ↳ TaskDetailActivity




## 🛠️ How to Run

1. **Clone this repository**

2. **Open with Android Studio**

3. **Build the Project**

4. **Run on Emulator or Device**


