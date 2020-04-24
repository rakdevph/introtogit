# introtogit
My fist attempt to use Git 


Here's what i did:
=================================================

1. Create a project (or within a project)
> cd <to you project>

2. Initialize git (git init)
> git init

3. Configure git. Add username and email to track who is working on the repository.
> git config --global user.name "Myusername"
> git config --global user.email "myemail@email.com"

4. Create .gitignore file
> touch .gitignore

5. Add excluded files to gitignore
6. Add files to staging
> git add . --> all files

7. Make initial commit
> git commit -m "Your notes or message here"


For trial changes, better to create branches or timeline:
> git  branch <branch name>

To switch to branch (for trial or temporary commit):
> git checkout <branch_name>

Note: changes to branch will not affect the master unless we want to merge all the branches
- First, switch to master
  > git checkout master

- git merge <branch name>

When everything is  final, upload to remote repository at github:
git remote add origin https://github.com/rakdevph/introtogit.git
git push -u origin master
