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
13. git stash:Temporarily saves your current changes and cleans the working directory without committing them
14. git stash pop:This command applies the most recently stashed changes and removes them from the stash list.
15. git stash clear:This command removes all the stashed entries, freeing up space and removing unnecessary stashed changes
16. git fetch --all --prune :This command fetches all branches from all remotes and prunes (removes) any branches that have been deleted on the remote.
17. git reset --hard upstream/main:This command resets your local branch to match the upstream/main branch exactly, discarding any local changes. Use with caution as it will delete all local changes that are not committed.
18. This command fetches and merges changes from the upstream/main branch into your current branch. If upstream is the remote repository's name, it will bring the latest changes from the main branch into your current branch