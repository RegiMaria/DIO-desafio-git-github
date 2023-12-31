## Main commands for working with branches

**HEAD **

HEAD is a TAG that indicates the current position in the commit history of the Git repository. It can point directly to a specific commit or to the name of a branch.

#### Git Checkout 

Command is used to navigate between branches in Git.

#### Git checkout -b

Creating a new branch and switching to it.

#### Merge

Merging integrates modifications made in different branches, bringing together distinct lines of development. It combines changes from different branches, facilitating the consolidation of diverse modifications.

​	_Fast-forward merge:_   when there are no divergences between the branches.

​	_Three-way merge:_ when there are divergences between branches. A new merge commit is created to incorporate changes from parent branches. Git attempts to automatically combine changes, but conflicts may arise that need to be resolved manually.

#### Deletar branch:

git branch -d <branchs name>

