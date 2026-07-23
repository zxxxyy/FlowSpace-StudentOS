# FlowSpace

## 📌 Overview

FlowSpace is a lightweight student productivity web application designed to help university students manage assignments, deadlines, and academic workloads more effectively.

Unlike traditional task management applications that only store to-do lists, FlowSpace helps students answer a more important question:

> "What should I work on today?"

FlowSpace analyzes assignments based on deadline urgency and difficulty level to provide smart priority recommendations, helping students focus on the most important tasks first.

---

## 🎯 Problem Statement

University students often manage multiple assignments from different courses, each with different deadlines and difficulty levels.

Without a structured system, students usually record assignments across different platforms or fail to track them consistently. As deadlines accumulate, it becomes difficult to determine which assignment should be prioritized.

This leads to:
- Last-minute submissions
- Poor time management
- Forgotten assignments
- Increased academic stress

Existing productivity tools provide basic task management, but many do not help students understand which task requires attention first.

FlowSpace was created to solve this problem by providing a simple academic productivity assistant that helps students organize, prioritize, and track their workload.

---

## 💡 Solution

FlowSpace transforms a traditional assignment tracker into an intelligent productivity assistant through:

- Assignment management
- Deadline-based priority calculation
- Difficulty-based workload consideration
- Daily focus recommendations
- Productivity progress tracking

Instead of only showing a list of tasks, FlowSpace highlights the most important assignments users should focus on today.

---

# 🚀 MVP Features

### 📚 Task Management
- Create assignments
- Edit assignments
- Delete assignments
- Mark tasks as completed
- Store notes and course information

### 🧠 Smart Priority Engine
Automatically calculates task priority based on:

- Deadline urgency
- Assignment difficulty

Priority levels:
- High
- Medium
- Low

### 🎯 Today's Focus
Provides a daily recommendation by highlighting the most urgent and important tasks.

### 📊 Progress Tracking
- Task completion percentage
- Completed vs pending assignments
- Upcoming deadlines overview

### 💾 Local Data Storage
- No backend required
- Data stored securely in browser localStorage
- Works as a lightweight single-user application

---

## 👥 Target Users

- University students
- College freshmen
- Students managing multiple assignments
- Learners who need better academic workload organization

---

# 🛠 Tech Stack

### Frontend
- React 18
- TypeScript
- Vite
- Tailwind CSS
- shadcn/ui

### Libraries
- date-fns
- lucide-react

### Storage
- Browser LocalStorage

---

# 🏗 Architecture

FlowSpace uses a lightweight client-side architecture:


React Application
|
|
Task Context
|
|
Priority Calculation Engine
|
|
LocalStorage Persistence


The application does not use a backend, authentication system, or external database to maintain simplicity and fast development.

---

# 🤖 AI-Assisted Development

This project is developed using an AI-assisted workflow.

AI is used to accelerate:
- Code generation
- Debugging assistance
- Architecture validation
- Development optimization

However, all technical decisions, feature selection, architecture design, and validation remain under developer control.

Development workflow:


Plan
↓
Architect
↓
Implement
↓
Verify
↓
Refine
↓
Deploy


---

# 📌 Future Improvements

Potential improvements:

- Calendar integration
- Assignment reminders
- Daily productivity streak
- Achievement system
- Advanced workload prediction
- AI-powered study recommendations
- Cloud synchronization
- Multi-user collaboration

---

## 📄 License

This project was created as part of the IndonesiaNEXT MVP development challenge.
