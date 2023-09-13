# Test-Repository
it's a repository for test
# Test-Repository
it's a repository for test
/* Git command */
first of all you need to create a repository in github at least you can initialize your project with the command : 
git init
after that you need to stage changes for commit to do that we use :
git add
so now we are stage oure change and to be sure if it's staged or no we can use the command :
git status
now we need to create a new commit wich means get a snapshoot of the change you have staged (added) so to do that we use : 
git commit -m "your description here"  //the '-m ' is used to include a commit message
then if we are in the main branch that's ok if not we need to change the branch to the main by :
git branch -M main
as also now we need to remote connection between your local git repository and github repository byu using :
git remote add origin https://github.com/your-username/your-repo-name.git
now to push your local branch, in this case, the "main" branch, to a remote repository named "origin" and set up a tracking relationship between your local branch and the corresponding remote branch. Let's break down this command:
git push -u origin main
to fetch changes from a remote repository and merge them into your current local branch we use the command :
git pull


