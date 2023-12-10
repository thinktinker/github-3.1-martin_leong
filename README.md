# Moddule 3.1 - Introduction to GIT I

## 1. Git commands

To set Name and Email Address used to identify the user commits in the Git history.
```
git config --global user.name "[Your Name]"

git config --global user.email "[youremail@example.com]"
```
\
Stage all the files for commit to the local repository.
```
git add .
```
\
Change an existing file path and stage the move.
```
git mv [existing-path] [new-path]
```
\
Delete a file from project and stage the removal for commit.
```
git rm [file]
```
\
Commit a file that is staged in a local repository.
```
git commit -m "[descriptive message]"
```
\
Unstage a file while retaining the changes in working directory.
```
git reset [file]
```
\
Push changes in a local repository to GitHub.
```
git push origin main
```
\
Show modified files in working directory, staged for next commit.
```
git status
```
\
Differences on change(s) to file(s) but not staged.
```
git diff
```
\
Compares the file version in a working directory with the file version last committed in a remote repository. The HEAD in the git command refers to the remote repository.
```
git diff HEAD [filename]
```
\
Fetch all branches from a Git remote.
```
git fetch [alias]
```
\
Retrieve an entire repository from a hosted location via URL.
```
git clone [url]
```
\
Fetch and merge any commits from the tracking remote branch.
```
git pull
```
\
List a local repository's branches. An asterisk (*) appears next to the currently active branch.
```
git branch
```
\
Create a new branch at the current commit.
```
git branch [branch-name]
```
\
Switch to another branch and check it out into a working directory.
```
git checkout
```
\
Merge the specified branch’s history into the current one.
```
git merge [branch]
```
\
Show all commits in the current branch’s history.
```
git log
```
## 2. References
https://kinsta.com/knowledgebase/install-git/
\
https://www.freecodecamp.org/news/git-and-github-for-beginners/
\
https://education.github.com/git-cheat-sheet-education.pdf
\
https://www.educative.io/answers/what-does-git-diff-head-filename-do
