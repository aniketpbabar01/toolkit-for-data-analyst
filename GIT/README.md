# 🚀 Git & GitHub CLI Workflow Guide for Interview Preparation

This guide helps you get started with GitHub using Git and GitHub CLI — perfect for Data Analysts, Developers, or anyone preparing for technical interviews.
## 🎥 YouTube References for Better Understanding

- [🔗 GitHub CLI & GitHub Project Walkthrough – Live Tutorial 1](https://www.youtube.com/live/DzFmUPGy55c?si=Pqg45Nezz-W_26Y-)

- [🔗 GitHub Projects, Git Bash, and ReadMe Setup – Live Tutorial 2](https://www.youtube.com/live/vSrvG1HKqaE?si=zuY1Z8L7qGxHtj4W)
---

## 📥 Install Git & GitHub CLI

### 🐙 GitHub CLI
- Visit: [https://cli.github.com/](https://cli.github.com/)
- Click **Download for Windows** and **Run** the installer.

### 🧰 Git
- Visit: [https://git-scm.com/downloads](https://git-scm.com/downloads)
- Click **Download for Windows** and **Run** the installer.

## Commonly Used GIT Commands in IT Company (Start with Git Bash)

1. (Optional) Install GitHub CLI via terminal:  
`winget install --id GitHub.cli`

2. Check Git version:  
`git --version`

3. Login & authenticate to GitHub:  
`gh auth login`  
Follow the prompt in terminal or browser.

4. Clone your GitHub repository using GitHub CLI:  
`gh repo clone aniketpbabar01/toolkit-for-data-analyst`  

5. Check current directory:  
`pwd`

6. Change directory using forward slashes `/` in Git Bash:  
`cd /c/Users/Admin/toolkit-for-data-analyst/GIT`

7. Add files to staging area (with Extension):  
`git add "filename.extension"`  
OR
Remove a file from Git tracking but keep it locally:  
`git rm --cached "filename.extension"`  

8. Commit the changes:  
`git commit -m "updating files"`
OR `git commit -m "removed files"`

10. Push changes to the main branch:  
`git push origin main`
OR To switch to a different branch:
`git switch branch-name`

11. Push changes to a new branch (e.g. update-readme):  
`git push -u origin update-readme`

12. Check pull request status:  
`gh pr status`

13. Create a pull request:  
`gh pr create --fill`

---
