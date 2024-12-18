# GIT EXERCISE

## BUNDLE 1

### EXERCISE 1

```bash

PS C:\Users\HP\git-exercises> history | Select-String git

git pull
git push origin delete README.md
git commit -m "Delete README.md"
git add --all
git commit -m "Delete README.md"
git push origin main
git push origin dev
git checkout master
git add --all
git status
git commit -m"Delete README.md"
git push origin master
git pull
git status
git add --all
git status
git status
git add --all
git commit -m"Delete README.md"
git push origin master
git checkout dev
git init
git checkout master
git branch -M main
git status
git status
git add README.md
git status
git commit -m"Init project"
git push
git status
git checkout master
git status
git push
git add README.md
git init 
git status
git status
git add README.md
git commit -m"Init project"
git push
git add README.md
git commit -m"Init project"
git push
git checkout -b dev
git checkout -b test
git branch -D test
git checkout -b dev
git branch -D test
git worktree list
git checkout -b dev
git checkout dev
git branch -D test
git push origin delete test
git push origin --delete test
git fetch origin
git push origin --delete test
git fetch origin
git status
git merge origin/dev
git push origin main --force
git push origin dev --force
history | grep git
``` 

### EXERCISE 2

``` bash

PS C:\Users\HP\git-exercises> history | Select-String git

git checkout dev
git status
git add home.html
git status
git stash
git stash list
git status
git add about.html
git stash
git stash list
git stash
git status
git add team.html
git stash
git stash list
git stash pop
git status
git add team.html
git stash
git stash list
git stash pop stash@{1}:
git stash pop stash@{1}
git stash pop stash@{1}:
git log
git log --oneline
git stash list
git stash pop stash@{1}
git status
git stash list
git stash pop stash@{2}
git stash pop "stash@{2}"
git status
git stash
git stash list
git stash pop "stash@{2}"
git stash pop "stash@{0}"
git add --all
git status
git commit -m"Stashing and unstashing home and about files"
git status
git stash pop "stash@{0}"
git status
git reset --hard
git status
git reflog
history | grep git

```
## BUNDLE 2

### EXERCISE 1 AND 2

```bash


git add --all
git commit -m"updated readme"
git push
git add --all
git commit -m"updated readme"
git push
git status
git checkout -b ft/bundle-2
git status
git status
git add -m "created service file"
git add service.html
git commit  -m "created service file"
git status
git push
git push --set-upstream origin ft/bundle-2
git status
git checkout master
git pul
git pull
git status
git checkout -b ft/servise-redesign
git status
git add -all
git add --all
git commit -m"service list"
git push
git push --set-upstream origin ft/servise-redesign
git add --all
git commit -m"updated README.md file"
git push
git checkout master
git pull
git add -all
git add --all
git commit -m"updated README.md file"
git push
git status
git pull
git status
git add -all
git add --all
git commit -m" changes in the service"
git push
git checkout ft/servise-redesign
git merge master
git status
git checkout master
git checkout ft/servise-redesign
git merge master
git add .
git commit -m"Changed file"
git push
git checkout master
git add .
git commit -m"changed files"
git push
git checkout ft/servise-redesign
git merge master
git checkout master
git .
git add .
git commit -m"changed files"
git push
git checkout master
git checkout ft/servise-redesign
git add .
git commit -m"changed files"
git push
git merge master
git merge master
git diff service.html
git checkout master
git status
git add .
git commit -m"delete file"
git push
git checkout ft/servise-redesign
git add .
git commit -m"delete file"
git push
git status
git checkout ft/bundle-2
git pull
git status
git add --all
git status
git status
git commit -m"changed service file"
git push
git checkout master
git add .
git commit -m"updated service"
git push
```
## BUNDLE 3

### EXERCISE 1 AND 2

```bash
PS C:\Users\HP\git-exercises> history | Select-String git

git add --all
git commit -m"updated readme"
git push
git add --all
git commit -m"updated readme"
git push
git status
git checkout -b ft/bundle-2
git status
git status
git add -m "created service file"
git add service.html
git commit  -m "created service file"
git status
git push
git push --set-upstream origin ft/bundle-2
git status
git checkout master
git pul
git pull
git status
git checkout -b ft/servise-redesign
git status
git add -all
git add --all
git commit -m"service list"
git push
git push --set-upstream origin ft/servise-redesign
git add --all
git commit -m"updated README.md file"
git push
git checkout master
git pull
git add -all
git add --all
git commit -m"updated README.md file"
git push
git status
git pull
git status
git add -all
git add --all
git commit -m" changes in the service"
git push
git checkout ft/servise-redesign
git merge master
git status
git checkout master
git checkout ft/servise-redesign
git merge master
git add .
git commit -m"Changed file"
git push
git checkout master
git add .
git commit -m"changed files"
git push
git checkout ft/servise-redesign
git merge master
git checkout master
git .
git add .
git commit -m"changed files"
git push
git checkout master
git checkout ft/servise-redesign
git add .
git commit -m"changed files"
git push
git merge master
git merge master
git diff service.html
git checkout master
git status
git add .
git commit -m"delete file"
git push
git checkout ft/servise-redesign
git add .
git commit -m"delete file"
git push
git status
git checkout ft/bundle-2
git pull
git status
git add --all
git status
git status
git add --all
git commit -m"changed service file"
git push
git checkout master
git add .
git commit -m"updated service"
git push
history | Select-String git
git status
git add --all
git commit -m"updated README.md"
git push
git pull
git push
git checkout -b ft/team-page
git status
git add .
git commit -m"created new HTML page"
git push
git push --set-upstream origin ft/team-page
git checkout master
history | Select-String git
git checkout master
git status
git checkout -b ft/contact-page
git log
git log -oneline
git log --oneline
git status
history | Select-String git
git status
git checkout ft/team-page
git status
git add .
git commit -m"created team page"
git push
git checkout master
git checkout ft/contact-page
git checkout ft/team-page
git log
git checkout ft/contact-page
git cherry-pick e521e9440c5c8172e7020accfa85a14973e29f59
git status
git add .
git commit -m"created a contact page"
git push
git push --set-upstream origin ft/contact-page
git status
git checkout -b ft/faq-page
git status
git add .
git commit -m"created an FAQ page"
git push
 git push --set-upstream origin ft/faq-page
git revert e521e9440c5c8172e7020accfa85a14973e29f59
git log
git push
git status
git checkout -b ft/home-page-redesign
git checkout master
git status
git add .
git commit -m"changes in the home page"
git push
git pull
git push
git checkout ft/home-page-redesign
git status
git log
git rebase master
git log
git status
git add .
git commit -m"changes in the file"
git push
git push --set-upstream origin ft/home-page-redesign

```