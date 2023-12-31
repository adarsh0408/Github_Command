# Github_Command

# GitHub Commands Cheatsheet

This README provides a quick reference for common Git commands used in GitHub workflows.

## Configure Git

Configure your global Git settings:

```bash
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
git config --list
```


<h3>Clone Repository</h3>

Clone a repository from a remote source:

`git clone <repository_link>`

<h3>Check Repository Status</h3>

Check the status of your local repository:

`git status`

<h3>Add Changes</h3>

Stage changes for commit:

`git add <file_name>`

To add all changes:

`git add .
`

<h3>Commit Changes</h3>

Commit staged changes with a descriptive message:

`git commit -m "Your commit message"
`

<h3>Push Changes to Remote</h3>

Push committed changes to the remote repository:

`git push origin main
`

<h3>Initialize Repository</h3>

Initialize a new Git repository:

`git init`

<h3>Add Remote Repository</h3>

Connect a local repository to a remote repository:

`git remote add origin <repository_link>
`

<h3>Check Remote and Branch</h3>

Check which remote repository you are working with:

`git remote -v
`

Check the current branch:

`git branch
`

<h3>Change Branch</h3>

Switch to a different branch:

`git checkout <branch_name>
`

Create and switch to a new branch:

`git checkout -b <new_branch_name>
`

<h3>Delete Branch</h3>

Delete a local branch:

`git branch -d <branch_name>
`

<h3>Compare Branches</h3>

Compare changes between two branches:

`git diff <branch_name>
`

<h3>Merge Branches</h3>

Merge changes from one branch into another:

`git merge <branch_name>
`

<h3>Pull Changes</h3>

Fetch and merge changes from the remote repository:

`git pull origin main
`

<h3>Resolve Merge Conflicts</h3>

Merge changes and resolve conflicts:

```
git merge <branch_name>
git push
```

<h3>Undo Changes</h3>

Undo staged changes:

`git reset <file_name>
`

Undo the last commit:

`git reset HEAD~1
`

Undo changes up to a specific commit:

`git reset <commit_hash>
`

Hard reset to a specific commit, discarding all changes:

`git reset --hard <commit_hash>
`

Fork (Web-based)
-


- Fork a repository on the GitHub website:

- Navigate to the repository on GitHub.

- Click the "Fork" button in the upper right corner of the page.


- This creates a copy of the repository under your GitHub account.


Clone the forked repository to your local machine:


`git clone <your_forked_repository_link>
`

- Add the original repository as a remote (upstream):

`git remote add upstream <original_repository_link>
`

Now you can fetch changes from the original repository and contribute to your forked version.