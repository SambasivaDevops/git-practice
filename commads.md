Git Command History with Descriptions
git init
Initializes a new Git repository in the current directory.

ls -al
Lists all files and directories in the current folder, including hidden ones, in a long format.

git status
Shows the current status of the repository, including staged changes, unstaged changes, and untracked files.

touch nibba.txt nibbi.txt
Creates two new empty files, nibba.txt and nibbi.txt.

rm hello
Removes the file named hello from the current directory.

git add nibbi.txt
Stages the file nibbi.txt to be included in the next commit.

git add nibba.txt
Stages the file nibba.txt to be included in the next commit.

git commit -m "first commit" nibba.txt
Commits the staged file nibba.txt with the message "first commit".

git config --global user.email "sambanandipaty@gmail.com"
Configures the global Git user email to associate with commits.

git config --global user.name "SambasivaDevops"
Configures the global Git username for commits.

git commit -m "first commit" nibba.txt nibba.txt
Attempts to commit the same file twice. This command will fail; only one instance of a file is needed.

git commit -m "first commit" nibbi.txt
Commits the file nibbi.txt with the message "first commit".

git rm nibba.txt
Removes the file nibba.txt and stages the removal for the next commit.

git restore nibba.txt
Restores the deleted file nibba.txt from the last commit.

git add nibba.txt
Stages the restored nibba.txt file.

git restore --staged nibba.txt
Removes nibba.txt from the staging area (unstages it).

git commit -m "nibba added again"
Commits the staged nibba.txt file with the message "nibba added again".

git reset nibba.txt
Removes nibba.txt from the staging area, but keeps any changes in the working directory.

git log
Shows the commit history of the repository.

git branch
Lists all the branches in the repository and highlights the current one.

git checkout -b dev
Creates a new branch called dev and switches to it.

git checkout master
Switches to the master branch (or main branch in modern naming conventions).

git checkout dev
Switches back to the
