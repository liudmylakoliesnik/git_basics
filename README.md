mkdir myproject
cd myproject
git init task1
cd task1
touch README.md
git add README.md
git commit
git commit -m "add(repo): initial commit"
git branch first_branch
git status
git add README.md
git status
git commit -m "README.md 1st subtask"
git checkout master
git status
git add README.md
git status
git commit -m "README.md 2d subtask"
git log --online --all
