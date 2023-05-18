Question 1: What version is git?
Answer 1: git version 2.25.1

Question 2: Record the git configuration.
Answer 2: user.email= jk115720@ohio.edu; user.name= Josh Khalil

Question 3: What happens when you issue the command "git --help"?
Answer 3: The git --help command gives many of the most common git commands and their use cases when entered.

Question 4: Check the status of your repository using the git status command.
Answer 4: The repository gives us a message saying nothing has been added to the staging area, and both README and answers.md files are untracked.
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README.md
        answers.md

nothing added to commit but untracked files present (use "git add" to track)

Question 5: What happens when you issue the command "git add <filename>"?
Answer 5: git gives an overview of which files are tracked in the staging area, and which files are untracked. See output below.
On branch master

No commits yet

Untracked files: 
	(use "git add <file>..." to include in what will be committed)
		README.md
		answers.md
	nothing addid to commit but untracked files present (use "git add" to track)
	
Question 6: What happens when you add a file to the staging area in git?
Answer 6: The repository adds the file to the staging area, and is ready to commit. See output below. 
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        answers.md
		
Question 7: What happens when you issue the status command after committing a file?
Answer 7: git adds the files to the local repository and saves the version to your local machine. We must issue the command "git push" to push to the remote repository. See output below.
On branch master
nothing to commit, working tree clean

Question 8: Record the output of git log as Answer 8.
Answer 8: commit 310f26cb56911db53c9e8a432d027b07d1b39e4a (HEAD -> master)
Author: Josh Khalil <jk115720@ohio.edu>
Date:   Thu May 18 08:50:53 2023 -0400

Initial Commit

