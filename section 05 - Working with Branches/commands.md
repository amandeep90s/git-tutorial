# Working with Branches

1. What is HEAD?

   In Git, `HEAD` is a reference to the commit currently checked out. Usually, it points to the current branch, which in turn points to its latest commit. When you make a commit, the current branch and `HEAD` move forward to that commit. In a detached `HEAD` state, `HEAD` points directly to a commit instead of a branch.

2. View branches command - This will diplay the list of all branches in your repository. Small asterisk symbol will be there for the current working branch.

   `git branch`

3. Create branch command - This will only create a new branch.

   `git branch <branch_name>`

4. Switch branch command - This will only switch to already created branches

   `git switch <branch_name>`

5. Switching and creating a branch at same time

   `git switch -c <branch_name>`

6. Switch to the branch with one checkout method

   `git checkout <branch_name>`

7. Switching and creating a branch at same time with one checkout method

   `git checkout -b <branch_name>`

8. Delete a branch

   `git branch -d <branch_name>` or `git branch -D <branch_name>`

9. Rename a branch

   `git branch -m <new_branch_name>`
