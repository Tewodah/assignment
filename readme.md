Git branches are effectively a pointer to a snapshot of your changes
Branches serve as an abstraction for the edit/stage/commit process
git branch -List all of the branches in your repository.
git branch <branch> - Create a new branch called ＜branch＞
git branch -d <branch> Delete the specified branch. 
git branch -m <branch>  Rename the current branch to ＜branch＞.
git branch -a - List all remote branches. 


Creating branches 
 command: git branch crazy-experiment (branch name) 
 The repository history remains unchanged. 
 All you get is a new pointer to the current commit:
 or on vs view terminal or terminal(...) > new terminal > 
 
 With the open terminal, type the command git branch name_of_the_branch.
To enter this new branch, you can also type git checkout name_of_the_branch.