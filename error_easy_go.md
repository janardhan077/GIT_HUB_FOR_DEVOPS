# ==============================
# 🔍 CHECK CURRENT STATE
# ==============================
git status              # see changed/untracked files
git branch              # current branch
git log --oneline       # commit history
git remote -v           # remote URL

# ==============================
# 📤 PUSH / PULL ERRORS
# ==============================
# "Everything up-to-date"
git status
git push origin master:main

# "src refspec main does not match any"
git branch
git push origin master:main

# "non-fast-forward"
git pull origin main --rebase
git push origin master:main

# ==============================
# 📦 STAGING FIXES
# ==============================
git add .               # stage all files
git reset               # unstage everything
git reset HEAD file     # unstage one file

# ==============================
# 🔙 UNDO COMMITS
# ==============================
git reset --soft HEAD~1   # remove last commit keep files
git reset --hard HEAD~1   # remove last commit delete files
git reflog               # recover lost commit
git reset --hard <id>    # restore old commit

# ==============================
# 🧹 CLEAN BAD FILES
# ==============================
echo "node_modules/" >> .gitignore
git rm -r --cached node_modules
git clean -fd            # remove untracked files/folders

# ==============================
# 🔄 SAVE WORK TEMPORARILY
# ==============================
git stash
git pull --rebase
git stash pop

# ==============================
# ✅ SAFE DAILY DEVOPS FLOW
# ==============================
git status
git add .
git commit -m "update"
git pull --rebase origin main
git push origin master:main
