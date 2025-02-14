A beginner-friendly guide to understanding and using Git and GitHub for version control and collaboration.

1️⃣ Git: Version Control System Git is a popular, free, open-source, fast, and scalable version control system that helps track changes in code.

Why Use Git? ✔ Track code history ✔ Collaborate with teams ✔ Revert to previous versions easily

2️⃣ GitHub: Code Hosting Platform GitHub is a web-based platform that allows developers to store, manage, and collaborate on projects using Git.

🔹 Think of GitHub like a folder, but in GitHub terms, it's called a Repository (Repo).

3️⃣ README File A README.md file contains essential project details: 📌 Project name 📌 How to use it 📌 Technologies used

4️⃣ Setting Up Git Before using Git, configure it with your details:

🔹 Global Configuration (Applies to all repositories)

git config --global user.name "Your Name" git config --global user.email "your@email.com" git config --list # View configuration 🔹 Local Configuration (For a specific repository) Used when working with multiple accounts.

5️⃣ Cloning a Repository & Checking Status Clone: Download a GitHub repository to your local machine.

git clone Status: Check the current state of your repository. git status

6️⃣ Essential Terminal Commands Command Description cd Change directory clear Clear terminal screen ls List all files/folders ls -a Show hidden files

7️⃣ Understanding File States in VS Code M (Modified): File has changes that are not yet staged. U (Untracked): New file not being tracked by Git. Staged: File is ready to be committed. Unmodified: No changes detected.

8️⃣ Tracking Changes: Add, Commit, Push 1️⃣ Add files to staging area git add # Add a specific file git add . # Add all files 2️⃣ Commit changes (save snapshot) git commit -m "Your commit message" 3️⃣ Push changes to GitHub git push origin main

9️⃣ Initializing a Git Repository To create a new Git repository: git init
git remote add origin # Connect to remote repo git remote -v # Verify remote connection git branch -M main # Rename branch to main git push origin main # Push to GitHub

🔟 Git Workflow GitHub Repo → Clone → Make Changes → Add → Commit → Push

1️⃣1️⃣ Working with Branches 1️⃣ Check current branches git branch 2️⃣ Switch to another branch git checkout 3️⃣ Create a new branch & switch git checkout -b 4️⃣ Delete a branch git branch -d

1️⃣2️⃣ Merging Code Method 1: Git Commands Compare branches before merging: git diff Merge branches: git merge Method 2: Pull Requests (PRs) Create a PR on GitHub to merge branches.

1️⃣3️⃣ Syncing with Remote Repo Pull latest changes from GitHub: git pull origin main

1️⃣4️⃣ Undoing Changes Case 1: Unstage Changes git reset git reset Case 2: Undo the Last Commit (Keep Changes) git reset HEAD~1 Case 3: Undo a Specific Commit git reset git reset --hard # Removes changes permanently

1️⃣5️⃣ Forking a Repository A fork is a copy of another repository that allows you to make changes without affecting the original repo.

🔹 Use it to contribute to open-source projects!

🎯 Now you’re ready to use Git and GitHub effectively! 🚀 This guide helps you understand the fundamentals of Git and GitHub, from setup to collaboration. Happy coding! 😊
