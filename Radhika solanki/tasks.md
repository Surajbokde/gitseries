**Task1**


1. What is git and gitHub?
Git- Git is a type of version control system that makes it easier to track changes to files or in the source code. It is designed for coordinating work among programmers, but it can be used to track changes in any set of files. It is a program installed in a system. 
Its current maintainer since 2005 is Junio Hamano. As with most other distributed version-control systems, and unlike most client�server systems, every Git directory on every computer is a full-fledged repository with complete history and full version-tracking abilities, independent of network access or a central server.

GitHub- It provides hosting for software development version control using Git. It allows us to create remote repository on website and provides a platform to bring teams together.
GitHub accounts are commonly used to host open source projects.

2. Why GitHub is so popular and used in most of the projects?
i. It supports all programing languages.
ii. Easily accessible 
iii. Provides secure cloud storage 
iv Teams can work together easily

3. What are the other platforms similar to GitHub?
i. SourceForge
ii. Launchpad
iii. GitBucket
iv Gitlab


**Task2**


a. How git workflow works?
  Git workflow has 4 fundamental stages: 
  i.   Workspace: Working Directory 
  ii.  Index (Stage): It is used as a staging area between working directory and your repository
  iii. Local Repository is the one on which we will make local changes, generally Local Repository is on our computer.
  iv.  Remote Repository is the one of the server.

b. What're the different stages of a git project as commit, add?
   Git project have 3 different stages
   i.   Modified: Once, the code is written in repository, anyone wants to make some modification can make those changes in their own remote repository.This is called Modification, i.e. making some additions to the original project.
   ii.  Staged: So, after making changes to the project without hampering the original version, but how do we apply those changes to our remote repository? So, we use the commands in the Git command line � git add. So, this command tracks the new changes and pushes it to the staging area where all the new files are finally ready to be joined to the remote repository.
   iii. Commit: This is the final stage, as this stage finally applies the new changes to the remote repository. commit is a set of new files that are being added to a project as part of the modification.

c. Is it possible to do a git commit before git add. If you have made any changes? Explain why?
   No, it is not possible to do git commit before git add. As per git workflow the file must be added to the index or staging area and then it must committed.Because when commit applies this simply means that you have successfully applied a certain modification to the code.

d. Why is git diff used?
   diff command is used in git to track the difference between the changes made on a file.

e. Can we leave the commit message as blank?
   Yes we can leave the commit message as blank and iCan we leave the commit message as blank?t can be done by using the command: git commit -a --allow-empty-message -m ""
**task3**
a)What is meant by the term fork and clone?

=>fork is a copy of original repository. By using fork we can get exact copy of original repository and we can update the files without disturbing original repository. Clone is a command which is used to get copy of remote repository to local repository.

b)what are branches in github?

=>Branches are use for development purpose without affecting other branches it is a Movable pointer to one of the commits.

c)What is PR?

=>PR is a pull request. By using PR we can request someone that we want to contribute to their open source project.

d)Can we delete the master branch if not why?

=>Yes

e)how can we delete a branch?

=>we can delete a branch by using command git branch -d branchname.