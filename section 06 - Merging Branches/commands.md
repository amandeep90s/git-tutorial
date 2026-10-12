# Merging Branches

1. Switch to or checkout the branch you want tomerge the changes into (the receiving branch)

2. Use the git merge command to merge changesfrom a specific branch into the current branch.

   `git switch main`
   `git merge <FEATURE_BRANCH_NAME>`

3. This Is Called A Fast-Forward - Main simply caught up on the commits from BRANCH_NAME

## Merge conflicts

A conflict occurs when Git cannot automatically combine changes from the branch being merged with changes on the receiving branch. This commonly happens when both branches edit the same lines, or when one branch deletes a file that the other branch edits. Git pauses the merge and marks the files that need your attention.

1. Run `git status` to see which files have conflicts.
2. Open each conflicted file and look for markers like `<<<<<<<`, `=======`, and `>>>>>>>`. Choose or combine the changes you want to keep, then remove the markers.
3. Stage each resolved file with `git add <FILE_NAME>`.
4. Finish the merge with `git merge --continue` (or `git commit` if Git asks you to create the merge commit).

If you do not want to continue, use `git merge --abort` to cancel the merge and return to the state from before it started.
