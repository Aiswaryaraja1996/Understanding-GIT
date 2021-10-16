# Understanding-GIT

### This repository contain various commands to use in GiTHub and understand the functions.

###### Git is a version control system that lets you manage and keep track of your source code history.
###### GitHub is a cloud-based hosting service that lets you manage Git repositories.
###### GitHub is a web-based interface that uses Git, the open source version control software that lets multiple people make separate changes to web pages at the same time.


- To clone a existing GIT repository
```
git clone https://github.com/Aiswaryaraja1996/Understanding-GIT.git
--- This creates a directory in your local with the repository name.

```

- To connect a local repository to git 
```
git init
--- git init command creates a new Git repository. It can be used to convert an existing, unversioned project to a Git repository or initialize a new, empty repository.

git remote add origin https://github.com/Aiswaryaraja1996/Understanding-GIT.git
--- used to add a remote repository as origin.The repository specified in the URL should exist.

```

- To add,commit and push the changes to a repository
```
git add .
--- git add command adds a change in the working directory to the staging area. It tells Git that you want to include updates to a particular file in the next commit.

git commit -m "My First Commit"
--- git commit command is used to move files from the staging area to a commit.git commit creates a snapshot of the changes made to a Git repository which can then be pushed to the main repository when the developer is ready to do so.
--- we can add any relevant message for our commits.

git push origin master
--- git push command is used to upload local repository content to a remote repository. Pushing is how you transfer commits from your local repository to a remote repo.

```

- To work with branches

```
--- A branch represents an independent line of development.

git branch
--- List all of the branches in your repository. This is synonymous with git branch --list.

git branch <branch>
--- Create a new branch called ＜branch＞. This does not check out the new branch.

git branch -d <branch>
--- Delete the specified branch. This is a “safe” operation in that Git prevents you from deleting the branch if it has unmerged changes.

git branch -D <branch>
--- Force delete the specified branch, even if it has unmerged changes. 

git branch -m <branch>
--- Rename the current branch to ＜branch＞.

git branch -a
--- List all remote branches.
```

- To create new branches

```
--- Branches are just pointers to commits. When you create a branch, all Git needs to do is create a new pointer to the current commit, it doesn’t change the repository in any other way.

git branch <branch-name>
--- creates a new branch.

git checkout ＜branchname＞
--- git checkout command lets you navigate between the branches created by git branch.

git push origin <branch-name>
--- push the changes to a particular branch alone.




