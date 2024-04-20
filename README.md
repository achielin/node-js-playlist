1.Cloning a Repository:
git clone https://github.com/iamshaunjp/node-js-playlist.git
Explore the repository's structure, files, and history:
cd to the repo
ls
git log

2.Forking a Repository:
Fork the repository to your GitHub account.
Clone the forked repository to your local machine:
git clone https://github.com/iamshaunjp/node-js-playlist.git 

3.Creating and Switching Branches:
Create a new branch:
git checkout -b feature-update
Switch to the newly created branch:
git checkout feature-update

4.Making Changes and Committing:
Make changes to a file or add a new file.
Commit the changes to the branch:
git add .
git commit -m "Add new feature"
Merging Changes:

5.Switch back to the main branch:
git checkout master
Merge changes from feature-update branch into the main branch:
git merge feature-update

6.Handling Conflicts
Creating Conflicts:
Make changes to the same file modified in Task 4.
Commit the changes:
git add .
git commit -m "Modify conflicting file"
Resolving Conflicts:

7.Create a new branch to resolve the conflict:
git checkout -b conflict-resolution
Resolve the conflict manually in the file.
8.Commit the changes and merge the branch back into main:
git add .
git commit -m "Resolve conflict"
git checkout main
git merge conflict-resolution
