# 📘 Git Tutorials – Complete Practice Repository

This repository contains all the Git commands and workflows I practiced to learn Git from beginner to intermediate level.  
It includes repository setup, staging, committing, branching, merging, and pushing changes to GitHub.

---

## 🚀 What I Learned in This Git Journey

### ✔ Initialize a Git Repository
    git init
## ✔ Check Repository Status
    git status
## ✔ Stage Files
    git add filename
    git add .    
## ✔ Commit Changes
    git commit -m "Commit message"
## ✔ Configure Username & Email
    git config --global user.name "yourname"
    git config --global user.email "youremail@example.com"
## ✔ Connect Local Repo to GitHub
    git remote add origin https://github.com/Sahajahanur/Git_Tutorials.git
## ✔ Push Local Branch to GitHub
    git push -u origin main
## ✔ Handle Push Error (Force Push)
    git push -u origin main --force
## 🌿 Branching & Merging Workflow
    git branch developer
## ✔ Switch Branch
    git checkout developer
## ✔ Work on Developer Branch
     git add test4.txt
    git commit -m "this is the new story i am working as developer"
## ✔ Switch Back to Main
    git checkout main
## ✔ Merge Developer Branch into Main
    git merge developer
## ✔ Push Updated Main to GitHub
    git push
## 🔄 Undo / Restore / Reset Commands
    git restore --staged filename
## ✔ Restore File to Previous State
    git restore filename
## ✔ Reset a Staged File
    git reset filename

 ## 📂 Files Created During Practice
 * README.md
 * test1.txt
 * test2.txt
 * test3.txt
 * test4.txt (created in developer branch → merged into main)

## 📜 Commit History (Git Log)
    git log
    git log -p -3
    
## 🌟 Skills Gained
* Git initialization
* Staging and committing
* Pushing and pulling
* Handling push errors
* Branching & merging
* Reset & restore
* Cloning repositories
* Maintaining clean commit history
## 🎉 Conclusion
This repository documents my complete Git learning journey.

I now understand how to use Git confidently with professional workflows including branching and merging.









