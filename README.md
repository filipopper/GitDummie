# GitDummie

commands needed to get started with git 👨‍💻💻
-------------------------------------------
Remember to replace the fields in single quotes with your data, the file called necessary commands which is inside the repository contains the basic commands for good management of git, check it out.

# Necessary

```diff
+git config --global user.name 'nombre' ->name that will appear when making a commit.

+git config --global alias.lodg 'log --oneline --decorate --graph'  ->create an alias.

+git config --global user.email 'mail'  ->email that will appear when making a commit.

+git config --global credential.username "usuario" ->username that will appear when making a commit.

+git branch --set-upstream-to=origin/master master ->link the origin/master (remote) branch to the local master branch(while on master) git pull = git pull origin master.
```
# Optional (it will make many things easier for you)

```diff
@@ git config --global color.ui true  ->automatically colorize most of the output it displays. @@

@@ git config --global pull.rebase true  ->used to ensure history is linear by avoiding unnecessary merge commits, "I want my changes to take precedence over what everyone else has done". @@

@@ git config --global alias.conflict 'diff --name-only --diff-filter=U'  ->when executed, performs a diff function on Git data sources. These data sources can be commits, branches, and files, among other possibilities. @@

@@ git config --global --list  ->list config @@
```
# Use it only in case you want to remove something

```diff
- git config --global --get-regexp alias**  ->looking for alias

- git config --global --unset alias.lodg**  ->remove alias

- git config --global --unset user.email**  ->Remove email

```




