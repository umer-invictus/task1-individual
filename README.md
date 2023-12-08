# How to achieved this task?
1) First i made the local repo by `git init` inside the project folder
2) Copy the CV to my project folder
3) Run the `git add .` to add the file in staging environment
4) When it is done, run the `git commit -m "first commit"` to commit it inside your local repo
5) Now time to add the remote repo, First i made the new repository on the github
6) Attacted the remote repo by using `git remote add origin https://github-ur`
7) Generate the token and add it with the remote repo url by using `git remote set-url origin https://<token>@github.com/username/repository.git`
8) Now push it to remote repo by `git push -u origin master`

## Commands Used
1) `git config --global user.name umer`
2) `git config --global user.email umerm6921@gmail.com`
3) `git init`
4) `git add .`
5) `git commit -m "first commit"`
6) `git remote add origin https://github-url`
7) `git remote push origin master`
