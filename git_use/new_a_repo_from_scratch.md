# Git Use From Scratch
`Author: YUAN Yanzhe @Jackthebighead`

### New a repo using git
  - first create a repo in GitHub, copy the SSH key.
  - then create a folder locally, and `git init` in the command window after entering the folder(`ls`,`cd` command...).
  - use `git remote add origin SSH_key` to establish access to the git hub.
  - use `git pull --rebase origin master` to pull the created repo on github to local folder.
    - alternatively use 'main' when you use 'main' as the NODE. 
 


### Update a repo using git
  - enter the folder, use `git init` for initialization.
  - use `git remote add origin SSH_key` to establish access to the git hub.
  - use `git pull --rebase origin master` to pull the newest version from Github.
    - use `git fetch all`, `git reset --hard original master`, `git pull` to even there is a difference between the repo in GitHub and your local folder (I prefer this way if there is some redundant file like .DStore file).
  -  drag or create or modify your files in this folder.
  -  use `git status` to check status of your local repo.
  - use `git add .` or `git add xxx.py` to add your file to the buffer.   
  - use `git commit -m 'the info you want to type'` to commit changes.
  - use `git remote add origin SSH_key` to establish access to the git hub.
  - use `git push -u master origin` to push your changes to the GitHub.
  - Done.

### Other methods
- Git Desktop
  - clone repo
  - pull repo to your local computer
  - add changes/updates in the corresponding folder
  - push to GitHub