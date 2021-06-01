# Git normal use
## Introduection for update file, undothings,how to use token and how to unadd file

### Copy the repo to your device
    git clone repo_URL
### Update to the latest repo in remote to your device
    git pull
### Modify the file and want to push to the remote
    1. git add modified_file
    2. git commit -m "write some notes here"
    3. git push
    4. enter token as password see the next topic to do so
### Use token to push the update
    1. go to github setting
    2. follow this up:
        https://docs.github.com/en/github/authenticating-to-github/keeping-your-account-and-data-secure/creating-a-personal-access-token
### Revert the file if delete in accident, or want to revert to the HEAD
    git checkout deleted_file
### If the file already add and want to cancel add action
    git reset file_want_to_unadd
### show log in short term
    git log --oneline
### only see the specific version 
    git show version_ID
## show log in pretty graph
    git log --all --decorate --oneline --graph (alias as git dog)