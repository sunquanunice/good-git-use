# good-git-use
## [How to Write a Git Commit Message](http://chris.beams.io/posts/git-commit/)
# [How to config for a template of git commit message](https://git-scm.com/book/en/v2/Customizing-Git-Git-Configuration)
 - First set an editor for git commit message in replace of git commit -m :

 	`git config --global core.editor 'subl -n -w'`

 - Then create a template file for the git commit message, such as `.gitmessage.txt` that looks like this:
```
 	Subject line

 	 What happened and why

 	 [Ticket : #x]
```
 - Finally configure the commit.template with the template file :

 	`git config --global commit.template ~/.gitmessage.txt`
