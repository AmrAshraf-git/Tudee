# 🤖 Tudee - Your Friendly Task Buddy

Too many tasks?
Still forgetting things?
Managing tasks feels boring?

Don't worry! Tudee is here to help!

---

## 📋 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Architecture](#architecture)
- [Tech Stack](#tech-stack)
- [Screenshots](#screenshots)
- [Getting Started](#getting-started)
- [Contributing](#contributing)
- [License](#license)


---

## 🌟 Overview

### 💡 What is Tudee?

**Tudee** is a lightweight colorful task management app designed to make organizing your day feel easy and encouraging.

No sign-in required – just open the app and start planning your day instantly!

With its cheerful robot companion, **Tudee** gives you friendly reminders and motivational messages to help you stay productive and positive.

The app stores data locally using the Room database and ensures a seamless user experience with Jetpack Navigation 2. It adheres to SOLID principles and maintains a clean, modular architecture.


<img width="1042" height="637" alt="who_is_tudee" src="https://github.com/user-attachments/assets/a143063d-f8b0-4617-9b8f-1c385b8bc9f8" />

---

## 🚀 Features
### Key features include:
- 🧾Fully Offline app using Local storage no need to open the internet
- 🎨 colorful and Smooth navigation
- 🧾 Classify tasks by status: To Do / In Progress / Done
- 🌐 Support for multiple languages (English and Arabic)
- 🌙 Dark mode and light mode support
- 🤖 Motivational messages from Tudee based on your task progress
- 🪄 No login required — just open and start working
- 🗓 Full task management (create, view, edit, delete)

### How does Tudee work?
When the user opens the app, they are immediately shown **today’s tasks**.

- ✅ They can **add a new task** for today using the “+” button.
- 📆 To browse or manage tasks for other days, they can navigate to the **“Tasks” tab** from the bottom navigation bar.
- 🔄 In the Tasks tab, the user can:
  - View tasks grouped by day
  - Filter tasks by status:
    - **To Do**
    - **In Progress**
    - **Done**
  - Add a new task for the currently selected date

Each task is associated with:

- 📂 A **Category** (e.g. Shopping, Cleaning, Worship, Family…)
- 📝 A **Title**
- 📄 An optional **Description**
- 📅 A **Date**
- ⚠️ A **Priority**
- 🏷️ A **Category**



### 🔹 Onboarding Screen
- Appears only on the first launch.
- Guides users through initial setup.

### 📊 Home Screen
- Displays statistics about today’s tasks.
- Shows task counts by status (To Do, In Progress, Done).

### ✏️ Task Creation
Users can create new tasks with:
- Title
- Description
- Priority
- Category
- Due date

### 🔍 Task Details
- View full details of any task.
- Update task status (To Do → In Progress → Done).

### 🔍 Task Filtering
- View all tasks based on a selected date.

### 🗂️ Category Management
- Predefined categories (e.g., Work, Personal, Study).
- Add custom categories with images from the device.
- Edit or delete custom categories.

### 🌗 Dark Mode & Light Mode
- Switch between dark and light themes.

### 🌍 Localization
- Automatically adapts to the device's language settings (English and Arabic).

### 📱 Responsive UI
- Supports various screen sizes and orientations.


---


## 🏗️ Architecture
1. ### ViewModels
    - Each screen has its own `ViewModel`.

2. ### Room Database
    - Stores task data locally.
    - Uses DAOs to interact with the database.

3. ### Dependency Injection
    - Uses **Koin** for DI.
    - Ensures higher-level modules do not depend on lower-level ones.

4. ### SOLID Principles
    - Adheres strictly to SOLID principles .

5. ### Clean Architecture (Lightweight)
    - Maintains a simple architecture without over-engineering.
    - Includes only necessary components.
  
---

  
## 🧱 Tech Stack

| Layer | Technology |
|-------|------------|
| Language | Kotlin |
| UI Toolkit | Jetpack Compose |
| Local Storage | Room Database |
| architecture | MVVM |
| unit testing  | Junit 5 & Truth & Mock & Coroutine & Turbine |
| Dependency Injection | Koin |
| Navigation | Navigation Component |


---
## 📸 Screenshots

- Home screen
- Add Task
- Task Screen
- Category Screen
- Add Category


🔆 Light Theme

| Home Screen | Add Task | Task Screen | Category Screen | Add Category |
|-------------|-------------|-------------|-------------|-------------|
| <img width="150" alt="home_screen" src="https://github.com/user-attachments/assets/28beddf6-3165-4a59-80fd-cb778987134f" /> | <img width="150" alt="add_task_screen" src="https://github.com/user-attachments/assets/d30ebb22-e831-45cc-91bf-590c240e4bc8" /> | <img width="150" alt="task_screen" src="https://github.com/user-attachments/assets/2032adae-bd72-4d92-a083-fa16a2bffd40" /> | <img width="150" alt="category_screen" src="https://github.com/user-attachments/assets/5e0412c7-a865-49cc-94e8-a0d90ea80951" /> | <img width="150" alt="new_category_screen" src="https://github.com/user-attachments/assets/1c7939e5-cff3-417e-8582-1dd7471354ce" /> | 


🌙 Dark Theme

| Home Screen | Add Task | Task Screen | Category Screen | Add Category |
|-------------|-------------|-------------|-------------|-------------|
| <img width="150" alt="home_screen_dark" src="https://github.com/user-attachments/assets/509368f9-63f8-4da2-873f-aa4eadb98f4f" /> | <img width="150" alt="add_task_screen_dark" src="https://github.com/user-attachments/assets/00ebf80c-470d-4042-af27-34c713962ae3" /> | <img width="150" alt="task_screen_dark" src="https://github.com/user-attachments/assets/1c4352e7-5ce1-4e95-90a8-4c9ba5b4fb14" /> | <img width="150" alt="category_screen_dark" src="https://github.com/user-attachments/assets/f4c32fef-ece9-4579-b08e-68de779b1337" /> |<img width="150" alt="add_category_screen_dark" src="https://github.com/user-attachments/assets/0d91149f-3374-496e-8502-1e3282fc2490" /> |


---


## ▶️ Getting Started

### Prerequisites

- Android Studio 4.2+
- JDK 11+
- Gradle 7.0+

---


## 🤝 Contributing

We welcome contributions!  
Whether you're a developer, designer, or just someone with a good idea — open an issue or send a pull request.

---

## 📄 License

Tudee is an open-source project licensed under the MIT License.  
This project was created as part of **The Chance** training program, Developed by **Berline Squad**
Feel free to use, learn from, and contribute to it.

---
