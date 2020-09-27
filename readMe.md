#github crash course
###initializing a repository
`git init .`
this command that convert folder to a git repository

###adding remote address of the repository
```git remote add origin https://github.com/Naman060504/ git-readme-crash-course.git```
git -> app 
remote -> command
add -> option 1
origin -> default container name.\
(url)-> `https://github.com/Naman060504/git-readme-crash-course.git`

### configure local repository user
```
git config --global user.name "naman060504"
git config --global user.email "namangupta060540@gmail.com"
```

### staging the files
staging->means we are telling git to monitoring/stage these files
`git add .`

### creating a local version /commiting changes
`git commit -m "message/changes"`
```
best practice for commiting messages
added/<what added>
updated/<what updated>
removed/<what removed>
```

### pushing changes to remote repository 
`git push <remote> <branch>`

example
`git push origin master`