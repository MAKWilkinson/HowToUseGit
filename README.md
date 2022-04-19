# How to Use Git

## 1. To Move A Local Folder Into GitHub

If you have created a new local repository and want to upload it to GitHub.

use 'cd HowToUseGit' from the terminal window to move out of the git directory and into the folder you have created.

Use 'git init' in terminal to initialise the folder when locally created.

Use  'git status' in terminal to check that you have untracked files.

Use 'git add .' in terminal to add all untracked files.

Use 'git commit -m "change heading" -m "change description" '.

Create a New Repo on GitHub and copy the link.

Use 'git remote add origin https://github.com/MAKWilkinson/HowToUseGit.git' using the link to the new repo you created.

Use 'git remote -v' to confirm your local repository is linked to the newly created one in github.

## 2. To Commit Changes to the Repository and Upload to GitHub

After making any changes in VS press save.

Use 'git status' in terminal to check if there are changed files.

Use 'git add .' in terminal to add all unchanged files.

You can check that this has worked using 'git status' in terminal again. 

Use 'git commit -m "change heading" -m "change description"' in terminal.

Use 'git push origin master' in terminal to upload these files to GitHub repo.

## 3. To Clone a Repository from GitHub to Local Drive

Click the Drop Down in the repository on GitHub and copy the link.

Use 'git clone https://github.com/MAKWilkinson/HowToUseGit.git' in terminal to clone the folder into your git directory.

Use 'cd HowToUseGit' in terminal to move into your cloned folder.

Repeat steps in Heading 2. to save and reupload your repository to GitHub.

## 4. Creating a Branch

Use "git branch" in terminal to check what branches are available in the current directory. 

Use "git checkout -b branchName" in terminal to create a new branch.

Use "git checkout branchName" in terminal to switch between branches.

## 5. Merging Branches - Making a Pull Request

### 5.1 Option 1 - Merge in Terminal using Git

Use "git diff master" in termianl to see all changes between the master and the branch you are currently in. press "q" in terminal to exit the interface after reviewing.

Change into your master branch using "git checkout master"

Use "git merge" in terminal to merge the two branches.

### 5.2 Option 2 - Push Back up to GitHub

Commit all changes to the new branch using steps above in 2.

Use "git push origin branchName" in terminal to push the branch up. 

A link will then appear in terminal, https://github.com/MAKWilkinson/HowToUseGit/pull/new/branchName, you can follow this which will create a pull request and give the option to merge the branches.

