Here's a list of some commonly used Git commands along with brief explanations:

1. **Configuration:**
   - `git config`: Set or get configuration options.
     - Example: `git config --global user.name "Your Name"`

2. **Initialization:**
   - `git init`: Initialize a new Git repository.

3. **Cloning:**
   - `git clone <repository_url>`: Clone a remote repository to your local machine.

4. **Status:**
   - `git status`: Show the status of changes as untracked, modified, or staged.
   
5. **Adding Changes:**
   - `git add <file>`: Add changes in a file to the staging area.
   - `git add .`: Add all changes in the working directory to the staging area.

6. **Committing:**
   - `git commit -m "Commit message"`: Commit staged changes with a message.

7. **Branching:**
   - `git branch`: List all local branches.
   - `git branch <branch_name>`: Create a new branch.
   - `git checkout <branch_name>`: Switch to a different branch.
   - `git merge <branch_name>`: Merge changes from one branch into the current branch.

8. **Remote Repositories:**
   - `git remote`: List remote repositories.
   - `git remote add <name> <repository_url>`: Add a new remote repository.
   - `git push <remote> <branch>`: Push local changes to a remote repository.
   - `git pull <remote> <branch>`: Fetch changes from a remote repository and merge them into the current branch.

9. **Log:**
   - `git log`: Show commit history.

10. **Tagging:**
    - `git tag`: List tags.
    - `git tag -a <tag_name> -m "Tag message"`: Create an annotated tag.

11. **Undoing Changes:**
    - `git reset`: Unstage changes.
    - `git revert <commit>`: Create a new commit that undoes a previous commit.
    - `git reset --hard <commit>`: Discard all changes after a specific commit.

12. **Stashing:**
    - `git stash`: Temporarily save changes that are not ready to be committed.
    - `git stash pop`: Apply the latest stash and remove it from the stash list.

These are just some of the basic Git commands. Git is a powerful tool with many features, so you may want to refer to the [official documentation](https://git-scm.com/doc) for more detailed information and advanced usage.
