# CMSE 802 Project
This repository contains my project for CMSE 802.

## Installation
1. Clone the repo:
   ```bash
   git clone https://github.com/YOUR_USERNAME/cmse802_project.git
   cd cmse802_project
2. Add .gitignore:
   ```bash
   cd cmse802_project
   touch .gitignore
   vi .gitignore
   
3. Add and Push
   ```bash
   git pull origin main --rebase
   git add .gitignore
   git commit -m "Added .gitignore for Python and Jupyter"
   git push origin main

4. Generate ssh key
   ```bash
   ssh-keygen -t rsa -b 4096 -C "your_email@example.com"
   cat ~/.ssh/id_rsa.pub
   git remote set-url origin git@github.com:YOUR_USERNAME/cmse802_project.git

5. Useful Command
   ```bash
   git status
   git log --oneline --graph
   git checkout COMMIT_ID
   git reset --hard COMMIT_ID
   git diff HEAD~1  # Compare with previous commit
   git diff COMMIT_ID COMMIT_ID  # Compare two specific commits   
