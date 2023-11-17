k Title: Set up new Git repository and create development branch for 'new-project'

Task Description:

As a developer, I need a new GitHub repository for 'new-project' and i need a development branch so that I can work on new features without affecting the main branch. 
Readme file should contain step-by-step instructions on how we can do it ourselves.

Expected Results:

A new branch called "development" is created and the user is able to switch to it successfully.
A new file called "README.md" is created and step-by-step instructions is added to it successfully.
The changes to the "development" branch are committed with a commit message successfully.
The changes from the "development" branch are merged into the "main" branch successfully.

Definition of Done (DoD):
1. mkdir new-project
2. cd new-project
3. git init
4. vi readme.md
5. git add readme.md
6. git commit -m "init"
7. git checkout -b development
git status
8. vi readme.md
9. git commit -m "add DoD to readme.md"
10. git checkout main
git merge development
11. git status
12. git commit -m "development2main"

https://github.com/YuriiMerkulov/new-project/blob/main/readme.md
