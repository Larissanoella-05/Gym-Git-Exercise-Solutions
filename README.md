# GIT EXERCISES

## Bundle 1

### Exercise 1

```bash
PS C:\Users\HP\git-exercises> git status
On branch master

No commits yet
PS C:\Users\HP\git-exercises> git branch -M main
PS C:\Users\HP\git-exercises> git status
On branch main

No commits yet
nothing to commit (create/copy files and use "git add" to track)
PS C:\Users\HP\git-exercises> git branch -M master
PS C:\Users\HP\git-exercises> git status
On branch master

No commits yet

nothing to commit (create/copy files and use "git add" to track)
PS C:\Users\HP\git-exercises> git status
No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README.md

nothing added to commit but untracked files present (use "git add" to track)
PS C:\Users\HP\git-exercises> git add README.md   
On branch master

No commits yet
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md

PS C:\Users\HP\git-exercises> git commit -m"First commit" 
[master (root-commit) 9b0bab8] First commit
 1 file changed, 3 insertions(+)
 create mode 100644 README.md
PS C:\Users\HP\git-exercises> git remote add origin https://github.com/Larissanoella-05/Gym-Git-Exercise-Solutions.git
fatal: The current branch master has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin master

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.

PS C:\Users\HP\git-exercises>  git push --set-upstream origin master
Counting objects: 100% (3/3), done.
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 269 bytes | 89.00 KiB/s, done.
To https://github.com/Larissanoella-05/Gym-Git-Exercise-Solutions.git
 * [new branch]      master -> master
branch 'master' set up to track 'origin/master'.
PS C:\Users\HP\git-exercises> git checkout -b dev 
Switched to a new branch 'dev'
PS C:\Users\HP\git-exercises> git status
On branch dev
nothing to commit, working tree clean
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin dev

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.

PS C:\Users\HP\git-exercises> ^C
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote:
remote: Create a pull request for 'dev' on GitHub by visiting:
remote:      https://github.com/Larissanoella-05/Gym-Git-Exercise-Solutions/pull/new/dev
remote:
To https://github.com/Larissanoella-05/Gym-Git-Exercise-Solutions.git
 * [new branch]      dev -> dev
branch 'dev' set up to track 'origin/dev'.
checkout : The term 'checkout' is not recognized as the name of a cmdlet, function, script file, or operable program. Check the spelling of the name, or if a  
At line:1 char:1
+ checkout -b test
+ ~~~~~~~~
    + CategoryInfo          : ObjectNotFound: (checkout:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException
 
PS C:\Users\HP\git-exercises> git checkout -b test
Switched to a new branch 'test'
fatal: The current branch test has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin test

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.

Total 0 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote:
remote:      https://github.com/Larissanoella-05/Gym-Git-Exercise-Solutions/pull/new/test
To https://github.com/Larissanoella-05/Gym-Git-Exercise-Solutions.git
 * [new branch]      test -> test
branch 'test' set up to track 'origin/test'.
PS C:\Users\HP\git-exercises> git checkout dev
Switched to branch 'dev'
Your branch is up to date with 'origin/dev'.
PS C:\Users\HP\git-exercises> git branch -D test
Deleted branch test (was 9b0bab8).
PS C:\Users\HP\git-exercises> git push origin  --delete test
To https://github.com/Larissanoella-05/Gym-Git-Exercise-Solutions.git
 - [deleted]         test

 ```
