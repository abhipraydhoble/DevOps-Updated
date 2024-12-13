# Day 2: Source Code Management Tool (Git)

## 1. Version Control Systems (VCS)

### Centralized VCS
- **Structure:** $${\color{red}\textbf{Single repository accessed by multiple users.}}$$
- **Example:** $${\color{blue}\textbf{SVN.}}$$

### Distributed VCS
- **Structure:** $${\color{red}\textbf{Each user has a local copy of the repository.}}$$
- **Example:** $${\color{blue}\textbf{Git.}}$$

---

## 2. Introduction to Git

### Definition
$${\color{red}\textbf{Git is a distributed version control system for tracking changes in code.}}$$

### Lifecycle
- **Working Directory:** $${\color{blue}\textbf{Files being modified.}}$$
- **Staging Area:** $${\color{blue}\textbf{Files prepared for a commit.}}$$
- **Repository:** $${\color{blue}\textbf{Final storage for committed changes.}}$$

---

## 3. Installing Git

### Steps
1. $${\color{red}\textbf{Download Git from the official website.}}$$
2. $${\color{red}\textbf{Install using default settings.}}$$
3. Verify the installation:
   ```bash
   git --version
   ```

---

## 4. Git Commands (Working on Local Repository)

### Initialize a Repository
```bash
git init
```

### Add Files to Staging
```bash
git add <file>
```

### Commit Changes
```bash
git commit -m "Commit message"
```

### Check Repository Status
```bash
git status
```

### View Commit History
```bash
git log
```

### Undo Changes
#### Revert a Commit:
```bash
git revert <commit>
```
#### Restore a File:
```bash
git restore <file>
```

---

# Day 3: Git Branching and Remote Repositories

## 1. Branching

### Commands
- **Create a Branch:**
  ```bash
  git branch <branch_name>
  ```

- **Switch to a Branch:**
  ```bash
  git checkout <branch_name>
  ```

- **Merge Branches:**
  ```bash
  git merge <branch_name>
  ```

- **View Differences:**
  ```bash
  git diff
  ```

---

## 2. Remote Repositories (GitHub)

### Commands
- **Clone a Repository:**
  ```bash
  git clone <repository_url>
  ```

- **Push Changes:**
  ```bash
  git push origin <branch>
  ```

- **Pull Updates:**
  ```bash
  git pull origin <branch>
  ```

- **Add a Remote Repository:**
  ```bash
  git remote add origin <repository_url>
  ```

---

# Day 4: Collaborating with GitHub

## 1. GitHub Dashboard

### Features
- **Public vs Private Repositories:**
  - **Public:** $${\color{red}\textbf{Accessible to everyone.}}$$
  - **Private:** $${\color{red}\textbf{Restricted access.}}$$

- **Forking and Pull Requests:**
  - **Fork:** $${\color{blue}\textbf{Copy a repository to your account.}}$$
  - **Pull Request:** $${\color{blue}\textbf{Propose changes to the original repository.}}$$

---

## 2. Authentication Methods
- **HTTP:** $${\color{red}\textbf{Username and password.}}$$
- **SSH:** $${\color{blue}\textbf{Secure key-based authentication.}}$$

---

# Day 5: Advanced Git and GitLab

## 1. GitHub vs GitLab

### Comparison
- **GitHub:** $${\color{red}\textbf{Popular for open-source projects; user-friendly interface.}}$$
- **GitLab:** $${\color{blue}\textbf{CI/CD integration, suited for enterprise solutions.}}$$

## 2. GitLab Editions

### CE vs EE
- **Community Edition (CE):** $${\color{red}\textbf{Free, open-source version.}}$$
- **Enterprise Edition (EE):** $${\color{blue}\textbf{Paid version with advanced features.}}$$

## 3. Resolving Merge Conflicts

### Steps
1. Merge the branch:
   ```bash
   git merge <branch_name>
   ```
2. Use your editor to resolve conflicts.
3. Commit the changes:
   ```bash
   git commit
   ```

---

## 4. Integrated Development Environment (IDE)

### Visual Studio Code
- **Installation:** $${\color{red}\textbf{Download from the [VS Code Website](https://code.visualstudio.com/).}}$$
- **Features:**
  - $${\color{blue}\textbf{Syntax highlighting.}}$$
  - $${\color{blue}\textbf{Extensions for Git and other integrations.}}$$
  - $${\color{blue}\textbf{Auto Git: Simplifies version control tasks.}}$$
