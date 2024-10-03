# 📝 Task Management App

This Flutter app allows users to create and manage tasks with basic CRUD (Create, Read, Update, Delete) functionality, including task priority features. The app uses `StatefulWidget` and `setState` for state management.

## ✨ Features

- 🆕 **Add Tasks**: Users can add tasks with a name and priority (Low, Medium, High).
- ✅ **Complete Tasks**: Users can mark tasks as completed or incomplete using checkboxes.
- 🗑️ **Delete Tasks**: Users can delete tasks from the list.
- 🔥 **Task Priorities**: Tasks can be assigned priorities (Low, Medium, High).
- 📊 **Sorting**: Tasks are automatically sorted by priority, with higher priority tasks appearing at the top of the list.

## 🗂️ Project Structure

The project is divided into several key parts:

1. **Task Model**: Defines the structure of a task object, which includes a name, completion status, and priority.
2. **Task Input**: Users can enter new tasks and assign a priority using a text field and a dropdown selector.
3. **Task List**: Displays the list of tasks in a `ListView`. Each task has a checkbox for completion status and a delete button.
4. **Task State Management**: The app uses `StatefulWidget` and `setState` to manage task additions, deletions, and updates.

## 📁 File Structure

```plaintext
task_management_app/
├── lib/
│   ├── models/
│   │   └── task.dart         # Task model
│   └── main.dart             # Main Flutter app with task management logic
├── .gitignore                # Flutter-specific gitignore file
└── pubspec.yaml              # Dependency file
```
## 🔨 Main Features Implementation
- Add Task Model: The Task class is defined in lib/models/task.dart to store task name, priority, and completion status.
- Add Task Input UI: The main screen includes a TextField for entering task names and a DropdownButton for selecting the priority.
- Add Task List Display: A ListView is used to display the list of tasks.
- Task Completion and Deletion: Each task in the list has a checkbox for marking it as complete or incomplete, and an icon button to delete the task.
- Add Task Priority: Users can assign a priority (Low, Medium, High) when adding a task. Tasks are automatically sorted by priority.

## 🚀 How to Run the App
1. Clone the repository:
  ```bash
  git clone https://github.com/SamiAhmed007/task_management_app.git
  cd task_management_app
  ```

2. Install dependencies:
  ```bash
  flutter pub get
  ```
3. Run the app:
  ```bash
  flutter run
  ```
## 🎓Extra Task:
This project includes an extra feature where users can assign priority to tasks and the app sorts them based on their priority levels. High-priority tasks are shown at the top.

## 🔮 Future Improvements
- 🗓️ Add due dates to tasks.
- 💾 Implement persistent storage (e.g., SQLite, SharedPreferences) to save tasks between app sessions.
- 🔔 Add notifications for high-priority tasks.
<!-- # task_management_app

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference. -->
