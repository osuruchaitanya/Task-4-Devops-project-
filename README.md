# 🚀 Task 4 – DevOps Project using Git & GitHub

This project demonstrates version control workflows using Git as part of my DevOps internship challenge.

---

## 📌 Objective

- Manage a DevOps project with Git best practices.
- Create proper branches, commits, pull requests, and tags.
- Document the complete workflow from start to finish.

---

## 🛠 Tools Used

- Git
- GitHub

---

## 🪜 Steps to Complete This Task

Below is a step-by-step record of what I did:

---

### ✅ 1. Initialize the Git Repository

```bash
git init


---

✅ 2. Connect to GitHub Remote

git remote add origin https://github.com/<your-username>/task-4-devops-project.git


---

✅ 3. Create the Initial README.md

echo "# Task 4 DevOps Project" > README.md
git add README.md
git commit -m "Initial commit with README"


---

✅ 4. Rename the Default Branch to main

git branch -M main


---

✅ 5. Push main Branch to GitHub

git push -u origin main


---

✅ 6. Create Additional Branches

Dev Branch:

git checkout -b dev
git push -u origin dev

Feature Branch:

git checkout -b feature/setup
git push -u origin feature/setup


---

✅ 7. Add a Sample File

echo "echo Hello from Task 4!" > hello.sh
git add hello.sh
git commit -m "Add hello.sh sample file"
git push


---

✅ 8. Create Pull Request from feature/setup to main

Go to GitHub

Click Compare & pull request

Review and Merge Pull Request



---

✅ Note: In some cases, you can also merge feature/setup → dev first, and then dev → main. Both workflows demonstrate branching.


---

✅ 9. Create .gitignore File

echo "node_modules/\n*.log\n.env\n.vscode/" > .gitignore
git add .gitignore
git commit -m "Add .gitignore file"
git push


---

✅ 10. Tag the Release

git checkout main
git pull
git tag v1.0 -m "First stable release for Task 4"
git push origin v1.0


---

🗂 Branches Created

main – Default production branch

dev – Development branch

feature/setup – Feature branch



---

🏷 Tag Created

v1.0 – First stable release



---

✅ Outcome

Through this project, I practiced:

Initializing repositories

Creating and switching branches

Committing changes

Pushing to GitHub

Using Pull Requests for merging

Tagging releases

Documenting workflows in Markdown
