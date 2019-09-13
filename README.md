# 9-17-2019
Git Practice, Guide, and Tutorial


# Standard Method to Use Git + Commands

```
git clone <Repository URL>

git branch -b <Branch Name>
```
Now you can add files/folders, delete files/folders, and/or make 
changes to existing files


After you have made your changes you use the following commands
```
git add <Filename>
```
to add a single file you changed or
```
git add .
git add -A
```
which adds all the changed files.

Now you have to commit these changes
```
git commit -m "Meaningful message about what you changed"
```

Now you can push your files.

If you created the branch locally you need to use this command
```
git push --set-upstream <Repository URL> <Branch Name>
```

If the branch already exists in the repository you can use
```
git push <Branch Name>
```
