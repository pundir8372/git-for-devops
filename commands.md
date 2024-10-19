#Git Commands Reference

1. Setup & Initialization
Create a new directory:

mkdir git-for-devops
mkdir git-basics

Navigate to a directory:

cd git-basics/

Initialize a Git repository:

git init

2. File Operations
Create new files:

touch nibba.txt nibbi.txt
vim hello-dosto.txt

List files:

ls
ls -a

3. Staging & Committing
Check status of files:

git status

Add files to staging area:

git add nibba.txt
git add nibbi.txt
git add hello-dosto.txt

Commit changes:

git commit -m "Added nibba and nibbi"
git commit -m "Added Hello-Dosto"

4. Viewing History
View commit history:

git log
git log --oneline

5. Branching & Switching
Create a new branch:

git checkout -b dev

Switch branches:

git switch dev
git switch master
git switch main

6. Modifying Files & Restoring
Edit files:

vim nibba.txt
vim nibbu.txt

Delete a file:

rm nibba.txt

Restore a deleted file:

git restore nibba.txt

7. Merging Changes
Add changes to a file and commit on a branch:

git add nibba.txt
git commit -m "Added new changes in the nibba"

8. Working with Branches
List all branches:

git branch

Switch back to a branch:

git checkout master
git checkout main

9. View History with Different Formats
View commit history in a simple format:

git log --oneline

Check the entire command history:

history
