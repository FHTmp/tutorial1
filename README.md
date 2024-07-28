# tutorial1

#cd tutorial1
#git init
#git status

#git add leapYear.java
#git ls-files 
#git ls-files --others 
#git reset leapYear.java
#git add . 

#echo "*.class" > .gitignore
#git add .gitignore
#git commit -m "Add .gitignore to ignore compiled Java class files"
#git push
#git status

#git status # Confirm there are staged changes
#git commit -m "First commit"
#git log --all --oneline--graph --decorate
#git tag -a v1.0 -m "First version 1.0"
#git tag

#git branch issue-1
#git log --all --oneline --graph --decorate 
#git branch
#git checkout issue-1
#git log --all --oneline --graph --decorate

#git diff Greeter.java
#git add Greeter.java
#git commit -m "Fixed bug"
#git log --all --oneline --graph --decorate 

#git branch feature-1
#git branch feature-2
#git checkout feature-1

#nano Greeter.java
Change line number 16: ‘name’ to ‘name.toUpperCase()’ in Greeter.java
#git diff Greeter.java #view the diff from git add Greeter.java
#git add Greeter.java
#git commit -m "Added feature 1"
#git checkout feature-2 

#nano Greeter.java
Change line number 16: ‘name;’ to `" "+name+" ";'
#git diff Greeter.java
#git add Greeter.java
#git commit -m "Added feature 2"
#git checkout main
#git merge feature-1 
#git log --all --oneline --graph --decorate
#git branch --merged 
#git merge feature-2 

#git status
#git add Greeter.java
#git commit -m “[tutorial1 w2]”
#git tag -a v1.1 -m "Two new features, version 1.1"
#git tag

#git remote add origin https://github.com/FHTmp/tutorial1
#git push --all origin
#git push origin --tags




