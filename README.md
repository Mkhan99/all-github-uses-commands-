https://github.com/
git config --global user.email "mkhabjkhjkkn@gmail.com"
git config --global user.name "mkhkljlkan"

1) git init
2) git add [filename] || -A
3) git status
4) git commit -m "msg"
5) git remote add origin reponame
6) git push origin master
7) git clone reponame
8) git pull origin master
90 git branch branch name
9) git branch master

-------------------------------------------------------------------


git config –-global user.name “[name]”
git config -–global user.email “[email address]”  
|=> This command sets the author name and email address respectively to be used with your commits.

git init 
|=> This command is used to start a new repository.

git add . OR [fileName]
|=> This command adds a file to the staging area. one or more to the staging area

git status  
|=> This command lists all the files that have to be committed.

git rm [file]  
|=>This command deletes the file from your working directory and stages the deletion

git log  
|=>This command is used to list the version history for the current branch.


git commit -m “[ Type in the commit message]” 
|=> This command records or snapshots the file permanently in the version history.

git commit -a  
|=>This command commits any files you’ve added with the git add command and also commits any files you’ve changed since then.

git show [commit]  
|=> This command shows the metadata and content changes of the specified commit


git clone [url]
|=>This command is used to obtain a repository from an existing URL



git branch  
|=>This command lists all the local branches in the current repository.

git branch [branch name]  
|=> This command creates a new branch.

git branch -a
|=> This command List all brance local and Remote

git branch -d [branch name]  
|=>This command deletes the feature branch.

git push origin --delete [branch name]
|=>Delete a remote branch


git checkout [branch name]  
|=>This command is used to switch from one branch to anothe

git checkout -b [branch name]  
|=> This command creates a new branch and also switches to it.

git checkout -b [branch name] origin/[branch name]
|=>Clone a remote branch and switch to it

git branch -m [old branch name] [new branch name]
|=>Rename a local branch

git checkout -	
|=>Switch to the branch last checked out

git checkout -- [file-name.txt]
|=>Discard changes to a file

git merge [source branch] [target branch]
|=> Merge a branch into a target branch

git merge [branch name]  
|=>This command merges the specified branch’s history into the current branch.

git remote add [origin] [Remote Server Link]  
|=>This command is used to connect your local repository to the remote server.


git diff
|=>This command shows the file differences which are not yet staged.

git diff –staged 
|=>This command shows the differences between the files in the staging area and the latest version present.

git diff [first branch] [second branch]  
|=>This command shows the differences between the two branches mentioned.

git reset [file]  
|=>This command unstages the file, but it preserves the file contents.

git reset [commit]  
|=>This command undoes all the commits after the specified commit and preserves the changes locally.

git reset –hard [commit] 
|=> This command discards all history and goes back to the specified commit.

git push [origin] master  
|=>This command sends the committed changes of master branch to your remote repository.

git push [origin] [branch]  
|=>This command sends the branch commits to your remote repository.

git push –all [origin]  
|=> This command pushes all branches to your remote repository.

git push [origin] :[branch name]  
|=>This command deletes a branch on your remote repository.

git pull [Repository Link]  
|=>This command fetches and merges changes on the remote server to your working directory

git stash save  
|=>This command temporarily stores all the modified tracked files.

git stash pop  
|=>This command restores the most recently stashed files.

git stash list  
|=>This command lists all stashed changesets.

git stash drop  
=>This command discards the most recently stashed changeset.

git stash
|=>Stash changes in a dirty working directory

git stash clear	
|=>Remove all stashed entries
















