# Anthem Workshop

## Project Title
Jana Gana Mana - National Anthem of India

## About the Project
This project was created as part of a Git and GitHub practice workshop. It demonstrates how multiple users can collaborate on a project using Git and GitHub.

## Technologies Used
- Git
- GitHub
# 🇮🇳 Anthem Workshop — Git & GitHub Practice

A hands-on project demonstrating Git version control, GitHub collaboration, feature branching, merging, conflict resolution, and commit recovery through a simple Flask-based National Anthem web application.

## 📌 Project Overview

The **Anthem Workshop** project provides practical experience with Git and GitHub workflows. It uses a simple Flask application to display India's national anthem title and related text while demonstrating collaborative software development practices.

## 🎯 Objectives

- Understand Git repository initialization and version control.
- Practice Git commits, branches, pushes, and pulls.
- Simulate collaboration between multiple contributors.
- Learn feature branch creation and merging.
- Identify and resolve merge conflicts.
- Inspect commit history and file changes using Git commands.
- Practice undoing and recovering commits using Git tools.

## 🛠️ Technologies Used

- **Programming Language:** Python
- **Web Framework:** Flask
- **Version Control:** Git
- **Repository Hosting:** GitHub
- **Frontend:** HTML

## 📁 Project Structure

```text
anthem-workshop1/
├── app.py
├── anthem.txt
├── templates/
│   └── index.html
└── README.md
```

## 🚀 Getting Started

### Prerequisites

Install Python, Git, and pip on your system.

### 1. Clone the repository

```bash
git clone https://github.com/naagashrivalliyallapu-ai/anthem-workshop1.git
cd anthem-workshop1
```

### 2. Create a virtual environment

```bash
python3 -m venv venv
```

Activate it on macOS or Linux:

```bash
source venv/bin/activate
```

### 3. Install Flask

```bash
python3 -m pip install Flask
```

### 4. Run the application

```bash
python3 app.py
```

Open the application in your browser:

```text
http://127.0.0.1:5000
```

## 🔀 Git & GitHub Exercises

| Exercise | Description |
|---|---|
| Repository Setup | Initialize and clone a Git repository |
| Collaboration | Simulate Satish, Rajesh, and Ramesh working on separate copies |
| Commit History | Inspect contributors using `git shortlog -sn` |
| Change Tracking | Identify line-level changes using `git blame` |
| Feature Branching | Create, push, merge, and delete a feature branch |
| Merge Conflicts | Create conflicting edits and resolve them |
| Commit Recovery | Practice undoing and recovering commits using Git |

## 💻 Useful Git Commands

```bash
git status
git log --oneline
git branch
git switch -c feature/new-feature
git add .
git commit -m "Describe your changes"
git push origin main
git pull origin main
git shortlog -sn
git blame templates/index.html
git reflog
```

## 📚 Learning Outcomes

After completing this workshop, learners should be able to:

- Manage source code using Git.
- Collaborate through GitHub repositories.
- Work with branches and merge changes.
- Resolve merge conflicts safely.
- Inspect project history and contributor activity.
- Understand how Git reflog helps locate previous repository states.

## 👨‍💻 Contributors

- **Satish** — Repository management and merge conflict resolution
- **Rajesh** — Flask application and HTML updates
- **Ramesh** — HTML page updates and collaboration workflow

*These names represent the contributor identities simulated during the workshop.*

## 🔗 Repository

[View Anthem Workshop on GitHub](https://github.com/naagashrivalliyallapu-ai/anthem-workshop1)

## 📄 License

This project was created for educational and Git & GitHub practice purposes. No specific open-source license has been assigned yet.
