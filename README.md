.Add repository locally
-create repository in Get Service (i.e. GitHub.com)
-copy path to repository
-open terminal and position to folder you want project folder be synced
-execute 'git clone %path%'

..to add commit execute in terminal in project folder: 'git add . && git commit -b "%comment"'

..to push changes to remote server execute 'git push -u origin %branch name%'

..managing branches
...to list branches execute 'git branch' - starred branch is selected one
...to add new branch execute 'git %new branch name%'
...to switch to another branch execute 'git checkout '%branch name%'
...to add new branch and switch selection to it execute 'git checkout -b %new branch name%'
...to merge branch switch to target branch and execute 'git merge %source branch%'