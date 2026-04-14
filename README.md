SOME CODE GIT FOR DEV
```bash
🚀 1. Init & Setup
    rm -rf .git                 # delete git completely
    git init                    # init repo
    git remote add origin <url> # connect to GitHub
    git clone <url>             # clone repo

📦 2. Commit (Daily)
    git status                  # check changes
    git add .                   # add all files
    git add <file>              # add specific file
    git commit -m "message"     # commit

☁️ 3. Push / Pull
    git push                    # push code
    git push -u origin main     # first push + set upstream
    git pull                    # pull latest code

🌿 4. Branch
    git branch                  # list branches
    git branch <name>           # create branch
    git checkout <name>         # switch branch
    git checkout -b <name>      # create & switch
    git branch -M main          # rename to main

🔄 5. Sync Code
    git pull origin main        # pull from main
    git pull --rebase           # cleaner pull (recommended)

💣 6. Fix & Undo
    git log --oneline           # view commits
    git reset --hard <commit>   # reset to commit
    git restore --staged <file> # unstage file
    git rm --cached <file>      # remove from git (keep local)
    git push -f origin main     # force push (danger)

🧪 7. Debug
    git log --oneline           # commit history
    git diff                    # file changes
    git reflog                  # recovery (very powerful)
