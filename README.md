# ✅ CheckMe – A Smarter To-Do List App

**CheckMe** is a cross-platform to-do list application built with **Flutter** and **Riverpod**, designed by **IRIZA Gatera Merveille**. It enables users to efficiently manage tasks through intelligent categorization, clean UI, due date tracking, and real-time task filtering.

> A productivity tool that works with you, not against you.

---

## ✨ Key Features

- 🔐 **Authentication** – Simple login with form validation
- 📝 **Task CRUD** – Create, edit, view, and delete tasks
- 🏷️ **Categories** – Organize tasks: Work, Personal, School, Urgent, General
- 🔍 **Search** – Instantly filter tasks by title or description
- 📅 **Due Dates** – Add and track deadlines with visual cues
- ✅ **Status Indicators** – Mark tasks as completed or pending
- 📄 **Task Details View** – Access full information and edit tasks

---

## 🧠 Built With

| Tech         | Description                     |
|--------------|---------------------------------|
| 🧱 Flutter    | UI framework for all platforms |
| ⚙️ Riverpod   | Scalable, robust state management |
| 🧪 Dart       | App logic and data modeling    |

---

## 📁 Project Structure

```

lib/
┣ 📄 todo.dart                # Todo model
┣ 📄 todo\_provider.dart       # Riverpod state management
┣ 📄 login\_screen.dart        # Login UI with validation
┣ 📄 home\_screen.dart         # Dashboard for task interactions
┣ 📄 todo\_details\_screen.dart # Detailed view and editing

````

---

## 💡 Application Flow

1. ✅ **Login Screen**  
   - Validates email and password  
   - Directs users to the home screen

2. 🏠 **Home Screen**  
   - View all tasks grouped by category  
   - Add tasks via a floating action button  
   - Search, filter, mark complete/incomplete  
   - Delete tasks with a long press  
   - Tap task to view/edit details  

3. 📄 **Task Detail Screen**  
   - Edit title, description, due date  
   - Update status  
   - Save changes

---

## 📸 Screenshots

_(Replace these with actual GitHub-uploaded screenshots)_

| Description                      | Screenshot                         |
|----------------------------------|-------------------------------------|
| Login form with validation       | `screenshots/login.png`            |
| Main dashboard view              | `screenshots/home.png`             |
| Adding a new task                | `screenshots/add_task.png`         |
| Viewing and editing task details| `screenshots/task_detail.png`      |
| Search results and filter views | `screenshots/search.png`           |
| Completed and pending status    | `screenshots/status.png`           |

---

## ⚙️ Getting Started

### 📌 Prerequisites

- Flutter SDK: [Install Flutter](https://flutter.dev/docs/get-started/install)
- Git

### 🛠 Installation

```bash
# Clone the repository
git clone https://github.com/Gatera-Me/CHECKME-To-do.git

# Navigate to the project directory
cd CHECKME-To-do

# Install dependencies
flutter pub get

# Run the app
flutter run
````

---

## 🧠 State Management – `todo_provider.dart`

```dart
class TodoNotifier extends StateNotifier<List<Todo>> {
  TodoNotifier() : super([]);

  void addTodo(Todo todo) { ... }
  void toggleComplete(String id) { ... }
  void deleteTodo(String id) { ... }
  void updateTodo(Todo updatedTodo) { ... }
}
```

* Pure functional updates using `copyWith`
* Riverpod ensures unidirectional and reactive state flow
* Fully testable and scalable

---

## 🧪 Future Enhancements

* ☁️ Cloud sync with Firebase/Supabase
* 👤 User registration & profile settings
* 🔔 Push notifications
* 🌓 Dark mode
* 🔁 Recurring tasks & reminders
* 🧾 Custom categories
* 🤝 Team collaboration

---

## 🤝 Contributing

Contributions are welcome!

```bash
# Fork the repo
# Create a feature branch
git checkout -b feature/my-feature

# Make changes and commit
git commit -m "Add: new feature"

# Push and open a PR
git push origin feature/my-feature
```

---

## 📄 License

Licensed under the [MIT License](LICENSE).

---

## 🙋‍♂️ About the Creator

**IRIZA Gatera Merveille**
📍 Kigali, Rwanda
📧 [gatemerveille@gmail.com](mailto:gatemerveille@gmail.com)
🔗 [github.com/Gatera-Me](https://github.com/Gatera-Me)

---
