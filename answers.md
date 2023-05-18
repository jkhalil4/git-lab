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

Question 9: Record the output of git status after pushing the repository to remote.
Answer 9: On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   answers.md

no changes added to commit (use "git add" and/or "git commit -a")

Question 10: Do the changes in README.md reflect in the online copy after committing it locally?
Answer 10: No. You must issue the command git push to push all changes from the commit area locally to the remote repository.

Question 11: Try the command git push and record the output.
Answer 11: Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 12 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 1.23 KiB | 1.23 MiB/s, done.
Total 4 (delta 0), reused 0 (delta 0)
To github.com:jkhalil4/git-lab.git
   310f26c..7047968  main -> main
   
Question 11: Issue the git pull command to pull changes from the remote repository to the local repository. See output below.
Answer 11: git gives the output "Already up to date" since all changes in the remote repository are synchronized.

Question 12: After issuing the command git pull and git push, do the online repository changes relect in the local copy? 
Answer 12: Yes, after issuing the push and pull commands, the file is up to date on github remote repository and the local machine.

Question 13: Issue the command ls -a and record the output. 
Answer 13: .  ..  .git  .gitignore  README.md