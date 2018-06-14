# GIT
## Steps to commit new project into git repository.  
```javascript
1. git clone https://github.com/bibhuti-developer/starter-mean-app.git

//see that all of your files are currently untracked in the working tree.
2. git status

// move inside the project directory
3. cd starter-mean-app/

4. git status

// stages our first commit using a special file called .gitignore, which lets us specify the parts of our  
// project that should be pushed to GitHub, and those that should remain just on our machine.
5. git add .gitignore

// to craft our first commit.
6. git commit -m "initials commit with .gitignore"

// stage the rest of the files
7. git add .

8. git status

9. git commit -m "initial version of commit"

10. git remote add origin https://github.com/bibhuti-developer/starter-mean-app.git

11. git push origin master
```
