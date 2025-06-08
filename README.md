# Git HTML Collaboration Demo

Welcome to the Git Workshop Project! 🎉  
This repository is part of an interactive hands-on Git session conducted by [Your Company Name] for first-year students.

## 📚 Objective

Learn and practice how real-world teams collaborate using Git and GitHub.  
You’ll work in small groups to contribute to a shared HTML/CSS/JS web project using feature branches, pull requests, and code reviews.

---

## 🛠️ Tech Stack

- HTML5
- CSS3
- JavaScript (Vanilla)
- Git & GitHub

---

## 📂 Project Structure

```
git-session/
├── index.html      # Base web page
├── style.css       # Styling for the page
└── script.js       # JS behavior and interactivity
```

---

## 🚀 Getting Started

1. **Clone the repo** (or accept the invitation to join the org).
2. **Create a feature branch** from `develop`:
   ```bash
   git checkout develop
   git checkout -b feature/<your-task-name>

3. Implement your feature (refer to the assigned issue).

4. Commit your changes:

    ```bash
    git add .
    git commit -m "Added <feature> - fixes #<issue-number>"
    ```

5. Push and create a Pull Request to develop.

---

### 🔀 Detailed Workflow

We follow a simplified but real-world Git workflow. Here's how it works:

1. **Base Branch – `develop`**  
   We've already added a basic HTML project to the `develop` branch. This acts as your **starting point**. All feature development must branch off from here.

2. **Creating a Feature Branch**  
   When working on a task, create a new branch using the following naming convention:
   ```
   feature/<task-name>
   ```
   Example:
   ```
   git checkout develop
   git checkout -b feature/add-about-section
   ```

3. **Implement Your Feature**  
   Make your changes in your local branch. Commit often with meaningful messages.

4. **Push and Create a Pull Request (PR)**  
   Push your branch to the remote and create a Pull Request (PR) targeting the `develop` branch.

   Example:
   ```bash
   git push origin feature/add-about-section
   ```

5. **Pull Request Review**  
   One of the mentors will review your PR. If everything looks good, your code will be merged into `develop`.

6. **Repeat for Each Task**  
   Every task or ticket should follow the same process — branching from `develop`, creating a PR, and merging back into `develop`.

---

## ⚔️ Learning Scenarios
- Branch creation and isolation of features
- GitHub Issues as tasks
- Pull Requests and code reviews
- Merge conflicts and resolutions
- Team collaboration practices

---

## 🤝 Contributors
This project is built collaboratively by the students participating in the Git Workshop, along with guidance from Altrium engineers.

---

## 📬 Questions?
Ask your mentors or instructors during the session. We're here to help!

Happy coding! 💻✨