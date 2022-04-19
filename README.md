# How to Use Git

If you have created a new local repository and want to upload it to GitHub.

use 'cd HowToUseGit' from the terminal window to move out of the git directory and into the folder you have created

Use 'git init' in terminal to initialise the folder when locally created

Use  'git status' in terminal to check that you have untracked files

Use 'git add .' in terminal to add all untracked files

Use 'git commit -m "change heading" -m "change description" '

Create a New Repo on GitHub and copy the link

Use 'git remote add origin https://github.com/MAKWilkinson/newdirectorylocal.git' using the link to the new repo you created

Use 'git remote -v' to confirm your local repository is linked to the newly created one in github

-------------------------------------------

## At this point it is as if you have cloned the file 

-------------------------------------------

After making any changes in VS press save.

Use 'git status' in terminal to check if there are unchanged files

Use 'git add .' in terminal to add all unchanged files

You can check that this has worked using 'git status' in terminal again 

Use 'git commit -m "change heading" -m "change description" '

Use 'git push origin master' in terminal to upload these files to GitHub repo
