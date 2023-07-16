# machine_learning_project
### Software and account Requirement.

1. [Github Account](https://github.com)
2. [Heroku Account](https://id.heroku.com/login)
3. [VS Code](https://code.visualstudio.com/)
4. [Git CLI](https://git-scm.com/downloads)

Creating Conda Enviroments
```
conda create -p venv python==3.7 -y
```
Activate conda enviroment
```
conda activate venv/

OR
```
Conda activate venv
```

To add files to git
```
git add .
```
OR
```
git add <file_name>
```
>Note : To ignore file or folder from git we can write name of file/folder in .gitignore

To check the git status
```
git status
```
To check all version maintained by git/At any point you can view the history of your changes using
```
git log
```
If you also want to see complete diffs at each step, use
```
git log -p
```
Often the overview of the change is useful to get a feel of each step
```
git log --stat --summary

A single Git repository can maintain multiple branches of development. To create a new branch named experimental, use
```
git branch experimental

you’ll get a list of all existing branches:
```
git branch
```
To create version/commit all changes by git
```
git commit -m "message whatever you want to type"
```
To send changes/version to git hub
```
git push origin main
```

To check Remote URL
```
git remote -v
```

Modify some files, then add their updated contents to the index:
```
git add file1 file2 file3
```
You are now ready to commit. You can see what is about to be committed using git diff with the --cached option:
```
git diff --cached
```
(Without --cached, git diff will show you any changes that you’ve made but not yet added to the index.) You can also get a brief summary of the situation with git status:
```
git status
```
If you need to make any further adjustments, do so now, and then add any newly modified content to the index. Finally, commit your changes with:
```
git commit
```
