1. git init: Initialize a new Git repository.
2. git status: Check the status of the repository, including the current branch, number of commits, and tracked/untracked changes.
3. git checkout -b <branch_name>: Create a new branch and switch to it.
4. git add <filename>: Stage a specific file for the next commit.
5. git add .: Stage all untracked files.
6. git commit -m "<message>": Commit staged changes with a meaningful message.
7. git remote add origin <repo_link>: Link the repository to a remote repository (e.g., GitHub).
8. git push -u origin master: Push changes to the remote repository and set the upstream tracking information.
9. git restore <filename>: Recover a deleted file from the system.
10. git branch: List all branches in the repository.
11. git restore --staged <filename>: Unstage a file (reverse git add).
12. git clone <repo_link>: clone the remote repository to your local system.
13. git log: Displays a detailed list of all changes made to the repository, including commit messages, author information, and dates.
14. git log --oneline: Displays a concise list of all commits, showing only the commit hash, author, and commit message.
15. git merge <branch_name>: Merges the specified branch into the current branch, preserving the commit history and creating a merge commit.
16. git merge --squash <branch_name>: Merges the specified branch into the current branch, squashing the changes into a single commit and simplifying the commit history.
17. git rebase <branch_name>: Rebases the current branch onto the specified branch, replays the commits from the current branch onto the latest commit in the target branch.
18. git rebase is used to:
=> Streamline a series of commits, creating a linear project history.
=> Keep a feature branch up-to-date with the main branch without creating a merge commit.
=> Move or combine a sequence of commits to a new base commit.
19. Git Rebase Example
To rebase a feature branch onto the master branch:
git checkout feature-branch
git rebase master