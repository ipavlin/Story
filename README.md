# README.md
## Section 17, AppBrewery, Command Line and Git

### git intro

```Zsh
git init .
git add .
git commit -m 'Some comment'
```

Get Swift.gitignore from github/gitignore -> .gitignore

```Zsh
git commit .gitignore
```

To see the history 

```Zsh
git log
```

to check the status of the files. 
```Zsh
	git status 
```
Red means not added to the staging area. Green means added to the staging area
It reports that nothing is on the staging area

To see the changes from one file to another (when you edit in the local repository)
```Zsh
git diff
```
Login on my account in  GitHub
*Be aweare that you do not store sensitive info on GitHub in Public repository*
GitHub private repositories are now also available up to three contributors

```Zsh
git remote add origin https://github.com/ipavlin/Story.git
git push -u origin master
```
Since I pushed, I can can get the files directly from the GitHub in a new directory

```Zsh
git clone 'http://www.github.com/ipavlin/Story.git'
```

I can remove the remote repository on GitHub by Settings->Manage->Danger Zone

### Branching and Merging
```Zsh
	git branch alien-plot			# Creates a new branch
	git branch								# lists all the branches
	git checkout alien-plot		# start using files on my-branch as if in master
	git branch								# recommended comand before switching back to master branch
	git checkout master				# puts you back on the master repository (complete snapshot)
```

You work indipendently on master and branch, than you merge the changes when both are in good state.

