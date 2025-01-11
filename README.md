# Welcome to Git and GitHub at ChaiCode Cohort!

## Introduction
Welcome aboard to the ChaiCode Cohort! Git and GitHub are essential tools for our development workflow, enabling version control, team collaboration, and efficient project management. This onboarding guide is designed to help you get started with Git and GitHub, ensuring a seamless experience as you contribute to our projects.

---

## Basics of Git and GitHub

### What is Git?
Git is a distributed version control system that allows developers to track changes in code, collaborate with team members, and maintain a history of project development. It is fast, reliable, and an industry standard.

### What is GitHub?
GitHub is a cloud-based platform that hosts Git repositories. It enhances team collaboration by providing tools for code review, issue tracking, and pull requests. At ChaiCode, GitHub is our central hub for managing code and teamwork.

---

## Installation and Setup

### Installing Git
#### Windows:

![Screenshot 2025-01-11 135602](https://github.com/user-attachments/assets/2a64026b-f37c-4e7f-a6a1-f001b4fbb2b5)
=======
1. Download the Git installer from [Git for Windows](https://git-scm.com/download/win).
2. Run the installer and follow the steps, selecting default options unless instructed otherwise.
3. Verify installation by running `git --version` in the terminal.

#### macOS:
1. Open the terminal and run:
   ```
   brew install git
   ```
2. Verify installation with:
   ```
   git --version
   ```

#### Linux:
1. Run the following command in the terminal:
   ```
   sudo apt update
   sudo apt install git
   ```
2. Verify installation with:
   ```
   git --version
   ```

### Configuring Git
After installation, configure your Git identity:
```
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```

### Creating a GitHub Account
![Screenshot 2025-01-11 161952](https://github.com/user-attachments/assets/e6eb29b9-c98b-4d3f-9063-6166405aef0a)

1. Go to [GitHub](https://github.com/).
2. Click **Sign up** and follow the steps to create your account.
3. Verify your email address and set up two-factor authentication for added security.

---

## Cloning the ChaiCode Repository

### Steps to Clone
1. Open your terminal.
2. Run the following command to clone the repository:
   ```
   git clone https://github.com/ChaiCode/example-repo.git
   ```
3. Navigate into the cloned folder:
   ```
   cd example-repo
   ```

---

## Basic Git Commands

### Frequently Used Commands
- **Check repository status**:
  ```
  git status
  ```
- **Stage changes**:
  ```
  git add <file-name>
  ```
- **Commit changes**:
  ```
  git commit -m "Your message here"
  ```
- **Push changes to remote**:
  ```
  git push
  ```
- **Pull updates from remote**:
  ```
  git pull
  ```
- **View commit history**:
  ```
  git log
  ```

---

## Commit Message Rules

### Guidelines
1. Use the **present tense** (e.g., "Add feature").
2. **Capitalize** the first letter.
3. Keep messages **short and descriptive** (50 characters or less).
4. Use prefixes for categorization:
   - `feat:` for new features.
   - `fix:` for bug fixes.
   - `docs:` for documentation changes.

#### Examples:
```
feat: Add tea selection feature
fix: Resolve login issue for tea enthusiasts
docs: Update README with chai varieties
```

---

## Branching Workflow
![github-flow](https://github.com/user-attachments/assets/5fe171d1-509f-48f5-b57a-5f45273a0d46)


### Branching Strategy
At ChaiCode, we use the following strategy:
- **main**: Production-ready code.
- **development**: Active development.
- **feature branches**: Individual features or fixes.

### Creating and Switching Branches
- Create a branch:
  ```
  git branch feature/tea-menu
  ```
- Switch to the branch:
  ```
  git checkout feature/tea-menu
  ```

### Merging Branches
1. Switch to the branch you want to merge into (e.g., `development`):
   ```
   git checkout development
   ```
2. Merge the feature branch:
   ```
   git merge feature/tea-menu
   ```
3. Resolve conflicts if necessary, then commit the merge.

---

## Pull Requests (PR)

![1_sMJbSt3sLrC-sIsPOVRBdw](https://github.com/user-attachments/assets/3f7eb1e4-fecb-48dc-9ae9-7466028ed5e8)

### Steps to Create a Pull Request
1. Push your branch to GitHub:
   ```
   git push origin feature/tea-menu
   ```
2. Go to the repository on GitHub.
3. Click **Pull Requests > New Pull Request**.
4. Select your branch and provide a clear description of the changes.
5. Request code reviews and address feedback promptly.

---

## Best Practices

1. Commit regularly with meaningful messages.
2. Pull updates frequently to avoid conflicts.
3. Review your code before committing.
4. Ensure branches are up-to-date before creating a PR.


Thank you for joining ChaiCode! Happy coding and collaborating!
