### 1\. Git setup : 

##### 

git --version



git config --global user.name "Your name"



git config --global user.email "your email"



### 2\. Start a Local Repository :



git init



### 3\. Connect Local Repo to Remote :



git remote add origin <remote-url>



git remote -v



git remote remove origin



### 4\. Clone Remote Repository :





git clone <remote-url>



### 5\. Check Repository :



git status



### 6\. Add Files to stagging :



git add <filename>



git add .        # add all files



git add -A       # add all including deletions



### 7\.  Commit Changes :



git commit -m "Your commit message"



git commit -am "Add + commit modified files"



### 8\. Push to Remote :



git push origin master



git push origin main



git push -u origin main



### 9\. Pull Updates from Remote :



git pull       # pull current branch



git pull origin main



### 10\. Fetch Changes (without merging) :



git fetch



git fetch origin



### 11\. Branch Operations :





git branch                  # list branches



git branch <name>           # create branch



git checkout <name>         # switch branch



git checkout -b <name>      # create + switch



git merge <branch>          # merge branch



git branch -d <name>        # delete branch



### 12\. View Changes :



git diff                    # unstaged changes



git diff --staged           # staged changes



git log                     # commit history



git show <commit-id>        # show specific commit



### 13\. Undoing Changes :



git restore <file>                      # undo file changes



git restore --staged <file>             # unstage



git reset --hard <commit-id>            # reset everything



git reset <commit-id>                   # soft reset



### 14\. Stash Changes : 



git stash



git stash list



git stash pop



### 15\. Tags :



git tag



git tag <tagname>



git push origin <tagname>



### 16\. Remove Files :



git rm <file>



git rm -r <folder>



### 17\. Clean Untracked Files :





git clean -f



git clean -fd



### 18\. Show Remote URLs : 



git remote -v

#### 



































