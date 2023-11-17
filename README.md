Task Description:

As a developer, I need a new GitHub repository for 'new-project' and i need a development branch so that I can work on new features without affecting the main branch. Readme file should contain step-by-step instructions on how we can do it ourselves.

Expected Results:

A new branch called "development" is created and the user is able to switch to it successfully. A new file called "README.md" is created and step-by-step instructions is added to it successfully. The changes to the "development" branch are committed with a commit message successfully. The changes from the "development" branch are merged into the "main" branch successfully.

Definition of Done (DoD):

mkdir new-project
cd new-project
git init
vi readme.md
git add readme.md
git commit -m "init"
git checkout -b development git status
vi readme.md
git commit -m "add DoD to readme.md"
git checkout main git merge development
git status
git commit -m "development2main"
https://github.com/YuriiMerkulov/new-project/blob/main/README.md
