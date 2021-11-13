# GitLearning

`git init`

`git add README.md`

`git commit -m "First Commit"`

`git remote add origin <REPO URL.git>`

`git push -u origin master`

`git pull origin master`

`git clone <REPO URL.git> my-custom-folder-name`

`git status` 

`git add .`  ***stage untracked files ( . | -A  | --all)***

`git rm --cached file.js` ***Deletes files both from the Git repository as well as the filesystem. Using the --cached***

`git log --oneline` 

`git log --prretty=oneline` 

`git branch feat/user-update` ***Create branch***

`git branch -d feat/user-update` ***Delete branch***

`git checkout feat/user-update` ***Switch to branch***

`git checkout -` ***Switch to last checkedout branch***

`git merge feat/user-update` ***Merge by checking out master branch***

`git reset HEAD` ***Moves all staged changed to unstaged***

`git reset --hard HEAD` ***Trashes changes to HEAD***

`gti checkout -CommitID file.js` ***Brings back changes from commit to staging area***

`gti diff -CommitID` ***Shows difference of current to ID***

`git config --list --local`

`git config --list --global`

`git config --list --system`

`git config --local --edit`

`git merge --abort`
