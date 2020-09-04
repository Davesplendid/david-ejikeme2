# david ejikeme

    9. What is a .git Directory?
    10. What happens if the .git directory gets deleted?

1. What is the difference between Git and Github?
	a.Git is an open-source distributed version control system (DVCS). it proves to be an excellent software. while GitHub is a Web-based Git version control repository hosting service.
   	b.Git is a software while GitHub is a service
	c.Git is installed locally on the system  While GitHub is hosted on  Web
	d.Git is a command line tool while GitHub provides a graphical interface
	e.Git is a tool to manage different versions of edits, made to files in a git repository WhilitHub is a space to upload a copy of the Git repository
	f.Git provides functionalities like Version Control System Source Code Management while GitHub provides functionalities of Git like VCS, Source Code Management as well as adding few of its own features


2. What are the benefits of using Version Control System? 
	Version control systems allow you to compare files, identify differences, and merge the changes if needed prior to committing any code.

3. What language is used in Git?
	Git used Programming language which is of high level language such as Javascript, python, C#

4. Mention the various Git repository hosting service providers (at least 4)
	The various Git repository hosting service providers are as follows
	a. GitHub
	b. GitLab
	c. Bitbucket
	d. SourceForge

5. What is a repository in Git?
	A repository in Git is the .git/ folder inside a project. This repository tracks all changes made to files in your project, building a history over time. Meaning, if you delete the .git/ folder, then you delete your project’s history.

6. How can you create a repository in Git?
	Repository in Git can be created using the following below;
	a.Create a directory to contain the project(cd c:).
	b.Go into the new directory.
	c.Type git init .
	d.Write some code.
	e.Type git add to add the files (see the typical use page).
	f.Type git commit

7. Name a few git Commands and explain their usage 
	Git Commands
	a. git config
	Usage: git config –global user.name “david-ejikeme”  
	Usage: git config –global user.email “davidbenyirmyahu@gmail.com”.This command sets the author name and email address respectively to be used with your commits.	
	b. git init
	Usage: git init [repository name].This command is used to start a new repository.
	c. git clone
	Usage: git clone [url]. This command is used to obtain a repository from an existing URL.
	d. git add
	Usage: git add [file]. This command adds a file to the staging area.
	Usage: git add * This command adds one or more to the staging area.
	e. git commit
	Usage: git commit -m “[ Type in the commit message]”. This command records or snapshots the file permanently in the version history.
	Usage: git commit -a  
	This command commits any files you’ve added with the git add command and also commits any files you’ve changed since then.
	f. git status
	Usage: git status. This command lists all the files that have to be committed.
8. What is Git?
 	Git is a distributed version-control system for tracking changes in source code during software development. It is designed for coordinating work among programmers, but it can be used to track changes in any set of files. Its goals include speed, data integrity, and support for distributed, non-linear workflows.

9. What is a .git Directory?
   The .git directory contains all the information that is necessary for your project in version control and all the information about commits, remote repository address, etc. All of them are present in this folder. It also contains a log that stores your commit history so that you can roll back to history.


10. What happens if the .git directory gets deleted?
	The folder will no longer be under versioning control.