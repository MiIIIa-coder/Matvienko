## Create ssh-key
- `ssh-keygen -t ed25519 -C "name.surname@phystech.edu"` in ~/.ssh --> make ssh keys
- `cat ~/.ssh/id_ed25519.pub` - show pub key
- `eval "$(ssh-agent -s)"` - client SSH use our key
- `ssh-add ~/.ssh/id_ed25519` - add our key
## Clone repository
- in github.com go to settings -> SSH and GPG keys -> new SSH key
- `git clone 'git@github.com:username/repository.git'` --> successCreate
## Check status of repository
- `git status`
## New file for commit
- `git add git-how-to.md`
- `git status`
## Create commit
- `git commit -m “initial commit”`
## Push changes to server
- `git push`
