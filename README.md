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
1. Go to [GitHub](https://github.com/).
2. Click **Sign up** and follow the steps to create your account.
3. Verify your email address and set up two-factor authentication for added security.

---

## Cloning the ChaiCode Repository

### Steps to Clone
1. Open your terminal.
2. Run the following command to clone the repository:
   ```bash
   git clone https://github.com/ChaiCode/example-repo.git
   ```
3. Navigate into the cloned folder:
   ```bash
   cd example-repo
   ```

---

## Basic Git Commands

### Frequently Used Commands
- **Check repository status**:
  ```bash
  git status
  ```
- **Stage changes**:
  ```bash
  git add <file-name>
  ```
- **Commit changes**:
  ```bash
  git commit -m "Your message here"
  ```
- **Push changes to remote**:
  ```bash
  git push
  ```
- **Pull updates from remote**:
  ```bash
  git pull
  ```
- **View commit history**:
  ```bash
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
```bash
feat: Add tea selection feature
fix: Resolve login issue for tea enthusiasts
docs: Update README with chai varieties
```

---

## Branching Workflow

### Branching Strategy
At ChaiCode, we use the following strategy:
- **main**: Production-ready code.
- **development**: Active development.
- **feature branches**: Individual features or fixes.

### Creating and Switching Branches
- Create a branch:
  ```bash
  git branch feature/tea-menu
  ```
- Switch to the branch:
  ```bash
  git checkout feature/tea-menu
  ```

### Merging Branches
1. Switch to the branch you want to merge into (e.g., `development`):
   ```bash
   git checkout development
   ```
2. Merge the feature branch:
   ```bash
   git merge feature/tea-menu
   ```
3. Resolve conflicts if necessary, then commit the merge.

---

## Pull Requests (PR)

### Steps to Create a Pull Request
1. Push your branch to GitHub:
   ```bash
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
