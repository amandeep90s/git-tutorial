# Commits in details

1. Always use present tenses while giving commit message

2. Changing default editor for git commits and other stuff

   `git config --global core.editor "code --wait"`

3. If you typed "git commit" only command inside terminal then default editor will open for giving commit message

4. One liner commit logs we can check with below command

   `git log --online`

5. We can show commit log ids in abbrevitaion mode

   `git log --abbrev-commit`

6. We can amend the last or previous commit only with below command

   `git commit --amend <commit_message>`

7. We can ignore any file or folder by adding `.gitignore` file in the project root location
