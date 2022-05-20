# GitDummie
 commands needed to get started with git 👨‍💻💻
-------------------------------------------
**the file called necessary commands contains the basic commands for good management of git ;)**

###Remember to replace the fields in single quotes with your data

git config --global user.name 'nombre' ->**name that will appear when making a commit**

git config --global user.email 'mail'  ->**email that will appear when making a commit**

git config --global color.ui true  ->**git will automatically colorize most of the output it displays. You can precisely adjust each of the parts to be colored; but if you want to activate all the default colors at once, you just have to set the color.ui parameter to "true"**

git config --global pull.rebase true  ->**can be used to ensure history is linear by avoiding unnecessary merge commits. Many developers prefer this option over merging, because it's like saying "I want my changes to take precedence over what everyone else has done."**

git config --global credential.username "usuario" ->**username that will appear when making a commit**

git branch --set-upstream-to=origin/master master ->**link the origin/master (remote) branch to the local master branch
(while on master) git pull = git pull origin master**

git config --global alias.lodg 'log --oneline --decorate --graph'  ->**create an alias**

git config --global alias.conflict 'diff --name-only --diff-filter=U'  ->**git diff is a multipurpose Git command that, when executed, performs a diff function on Git data sources. These data sources can be commits, branches, and files, among other possibilities.**

git config --global --list  ->**list config**

+ **git config --global --get-regexp alias**  ->**looking for alias**

+ **git config --global --unset alias.lodg**  ->**remove alias**

+ **git config --global --unset user.email**  ->**Remove email**
