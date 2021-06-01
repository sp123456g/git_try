# Git normal use

## copy the repo to your device
    git clone repo_URL
## update to the latest repo in remote to your device
    git pull
## modify the file and want to push to the remote
    1. git add modified_file
    2. git commit -m "write some notes here"
    3. git push
    4. enter token as password see the next topic to do so
## Use token to push the update
    1. go to github setting
    2. follow this up:
        https://docs.github.com/en/github/authenticating-to-github/keeping-your-account-and-data-secure/creating-a-personal-access-token

## revert the file if delete in accident
    git checkout deleted_file
