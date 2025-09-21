# to discard changes in a specific file:
git checkout--<file-name>
git checkout .
git restore
# commit history of current branch in readable format
git log --oneline --graph -all

# create new branch feature/patient
git checkout -b feature/patient

# made commits locally uploading in remote repo
git push --set-upstream origin feature/branch
git push

# to see all branches present
git branch -a

# to configure to remote repo
git remote -v

# to see fetch latest state of the remote repository
git fetch origin

# compare your local main branch with the remote 'origin/main'
git diff main origin/main

# if local branch is behind remote then we use git stash
git stash 
git pull origin main
git stash pop

# delete an branch from remote
git push origin --delete hotfix.login-bug

# how to apply a patch file
git apply name-ofpatch-file.patch

git status
git diff

git add .
git commit -m "apply patch for reason for patch"
