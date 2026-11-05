# Лабораторная работа №6: Система контроля версий

## Лог команд 
```bash
git config --global user.name "..."
git config --global user.email "..."
git clone https://github.com/liska14/lab6.git
git pull origin main
git log --oneline --graph --all
git checkout -b feature-branch
git add .
git commit -m "..."
git checkout main
git merge feature-branch
git branch -d feature-branch
git checkout -b report-branch