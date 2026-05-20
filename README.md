USed Git commands with explanations

## 🏗️ Task 1:The Basics

### 1. Initialize a New Repository
*   Create a new local Git repository for your project. ✅ 
*   -git init
        -Creates a new local Git repository in the current folder.


*   Make your very first commit. ✅ 
*   -git add README.md
        -Stages the new file so Git will include it in the next commit.

*   -git commit -m "Initial commit"
        -Records the staged change in the repository history with a message.


### 2. Connect to GitHub
*   Create a new repository on GitHub. ✅ 


*   Link it to your local repository. ✅ 
*   -git remote add origin https://github.com/FSopelsa/Git-workshop.git
        -Adds a new remote named origin that points to the GitHub repository URL.

### 3. Track Changes
*   Create and modify files.
*   Stage and commit changes, and **push** them to GitHub.
*   Create a few more files (e.g., `notes.txt`, `README.md`).
*   Make several commits to practice **meaningful commit messages** and version tracking.

### 4. Ignoring Files
*   Create a `.gitignore` file.
*   Configure it to exclude unnecessary or sensitive files from being tracked.