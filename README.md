# Git-Practice-Mohammad-Hasweh

## 1. What is the difference between Git and GitHub?

- A **distributed version control system** called **Git** enables programmers to monitor source code modifications while creating software.

- One **web-based platform** that hosts Git repositories online is **GitHub**. It offers project management tools, pull requests, and problems as collaboration capabilities.

---

## 2. Explain the difference between `git pull` and `git fetch`.

- The command `git fetch` pulls files, references, and commits from a remote repository **without merging** them into your local branch. Your current working branch stays the same, but your local copy of the remote branch is updated.

- `git pull`: Executes a **merge** after a `git fetch`. Changes are automatically incorporated into your current branch after being downloaded from the remote.
---

## 3. What is the purpose of `.gitignore` file?

The `.gitignore` file specifies intentionally untracked files that Git should ignore. This includes files like:
- Environment-specific files (`.env`, local configs)
- IDE/editor configs (`.vscode/`, `.idea/`)

This guarantees that no unnecessary or sensitive files are committed and keeps your repository tidy.
---

## 4. Describe the steps to contribute to an open-source project on GitHub.

1. **fork** the repository.
2. **Clone** the forked repository to your computer:
   ```bash git clone https://github.com/Mohammad-Hasweh/Git-Practice-Mohammad-Hasweh.git
3. **Create** a new branch to work on the feature or fix
4. **Make** Your Changes
5. **Stage** and **Commit** Your Changes
6.  **Push** the Changes to Your Fork
7. Create a **Pull** Request