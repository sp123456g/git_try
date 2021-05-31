# How to create branch and merge
## How to create branch?
### 1. create branch
    git branch branch_name
### 2.check how many branch we have here
    git branch
### 3. check 
    go to the branch we want to edit
### 4. edit file
    create a file and do some change in the new file
### 5. add file and commit 
    git add file
    git commit -m "make some note"
### 6. push to the remote branch
    git push orign branch_name
### 7. merge to the master if you want
    git merge branch_name
### 8. if need to delete branch
    git branch -d branch_name
### 9.if the branch didn't be merged yet: use -D to force delete
    git branch -D branch_name
### 10. delete branch in remote branch
    git branch origin :branch_name
### 11. rename the branch in the remote branch
    git branch origin branch_name:remote_branch_name