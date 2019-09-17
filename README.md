# 9-17-2019
Git Practice, Guide, and Tutorial


# Standard Method to Use Git + Commands

```
git clone <repository url>

git branch -b <branch name>
```
Now you can add files/folders, delete files/folders, and/or make 
changes to existing files


After you have made your changes you use the following commands
```
git add <filename>
```
to add a single file you changed or
```
git add .
git add -A
```
which adds all the changed files.

Now you have to commit these changes
```
git commit -m "meaningful message about what you changed"
```

Now you can push your files.

If you created the branch locally you need to use this command
```
git push --set-upstream <repository url> <branch name>
```

If the branch already exists in the repository you can use
```
git push <branch name>
```
