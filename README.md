# Git
# Git--demo
#What is git ?
Git is a version control system. 
It helps you keep track of changes made to your files and projects over time. 
Think of it as a tool that saves every update you make, so you can go back to previous versions or see what changes were made by others.

#what is version contral system?(record changes)
Simple Explanation:
It remembers what changes were made to your codes and when.
If something goes wrong on code, you can return to an earlier version of your code.
It is multiple people uploaded there code and without losing each other’s code.

#VCS are 3 types LCS, CVCS and DVCS
Local Version Control System (LVC): Tracks changes to code on your local computer.
Centralized Version Control System (CVCS): Stores code and their history on a central server, and users check in or check out code.
Distributed Version Control System (DVCS): Each user has a full copy of the entire repository, including its history (e.g., Git).

------------------------------------------------------------------------------------------------------------------------------------------------------------------

#Table comparing Git and GitHub 
Feature	                                Git	                                                         GitHub
What                   it is	A tool to track and save changes in your files.        	A website to store and share your Git projects online.
Where                  it works	On your computer.	                                    Online, on the internet.
Main Purpose	         Keeps a record of changes you make to your files.            	Lets you share your project and work with others.
Internet needed?       No, works offline.                                           	Yes, works online.
What it helps with	   Keeps history of your work and manages updates.	              Lets you store your project and collaborate with others.


------------------------------------------------------------------------------------------------------------------------------------------------------------------

#Install git in windows
1 Download git from
  https://git-scm.com/downloads

 2 Install it
    Open Git Bash and run git command
 3.git version
 
 -------------------------------------------------------------------------------------------------------------------------------------------------------------------
 
 Set up on Linux
1.sudo apt update(Updates the list of available packages on linux.)
2.sudo apt upgrade(Upgrades all installed packages to their latest versions)
3.sudo apt install git(Installs the Git version control software on linux)


-----------------------------------------------------------------------------------------------------------------------------------------------------------------

1. Git Repository
A Git repository (repo) is where your project files and their version history are stored.
You can create a local repository on your computer or clone an existing one from a remote server.
--------------------------------------------------------------------------------------------------------------------------------------------------------
2. Git Clone
Command: git clone <repository-url>
Purpose: Creates a copy of a remote repository on your local machine.
Use Case: When you want to start working on a project that is already hosted on a platform like GitHub.

----------------------------------------------------------------------------------------------------------------------------------------------------------------
4. Git Pull
Command: git pull
Purpose: Updates your local repository with the latest changes from the remote repository.
Use Case: Before you start working on a feature, you should pull the latest changes to ensure your local copy is up to date.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------
6. Git Branch
Command: git branch <branch-name> (to create a branch)
Purpose: Allows you to create separate lines of development.
Use Case: Use branches to work on new features or fixes without affecting the main codebase (usually main or master).

-----------------------------------------------------------------------------------------------------------------------------------------------------------------
8. Git Checkout
Command: git checkout <branch-name>
Purpose: Switches to the specified branch.
Use Case: After creating a branch, you need to check it out to start working on it.



----------------------------------------------------------------------------------------------------------------------------------------------
10. Git Commit
Command: git commit -m "Your commit message"
Purpose: Saves your changes to the local repository.
Use Case: After making changes, you should commit them with a descriptive message to document what you’ve done.

=---------------------------------------------------------------------------------------------------------------------------------------------------
12. Git Push
Command: git push origin <branch-name>
Purpose: Uploads your local commits to the remote repository.
Use Case: After committing your changes, push them to share with others or to back them up.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------
13. Git Merge
Command: git merge <branch-name>
Purpose: Combines changes from one branch into your current branch.
Use Case: After finishing a feature on a separate branch, you merge it back into the main branch to include the new changes.


---------------------------------------------------------------------------------------------------------------------------------------------------------
9.Git Pull Request (PR)
Use Case: After pushing your branch to the remote repository, you can create a pull request to propose merging your changes into the main branch.

----------------------------------------------------------------------------------------------------------------------------------------------------------

Process:
Go to your repository on GitHub/GitLab.
fix the commit 
create branche 
Click on "New Pull Request".
Select the branch you want to merge and provide a description.
Submit the pull request for review.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------


Real-Time Workflow Example:
Clone the Repository:git clone https://github.com/username/repo.git
Change Directory:cd repo
Pull Latest Changes:git pull
Create a New Branch:git branch new-feature
Switch to the New Branch:git checkout new-feature
Make Changes: Edit files as needed.
Stage Your Changes:git add .
Commit Your Changes:git commit -m "Added new feature"
Push the Changes to Remote:git push origin new-feature
Create a Pull Request: Go to the repository on GitHub/GitLab and submit a PR for new-feature to be merged into main.




