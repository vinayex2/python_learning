To add ssh authentication

1. ssh-keygen -t rsa -b 4096 -C "your_email@example.com"
2. Press enter to continue or add phrases
3. ssh-add ~/.ssh/id_rsa
4. git config --global user.email "vinayex2@gmail.com"
5. clip < ~/.ssh/id_rsa.pub
6. paste the ssh key into github acccount ssh page under settings








To setup a new repository

1. Create an empty repo on git hub
2. Use git bash to cd to a folder where you code is present
3. Create a .gitignore file and add all paths that git should not push to the repo
4. git init
5. git add .
5. git status
6. git commit -m "Comment about this commit"


Now you are ready to push the content to the repository

7. git remote add origin <i>remote repository url</i>
8. git remote -v (remove remote repo by git remtoe remove <i>reponame</i>
9. git push origin master    (pushes to master/main branch)

~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
