# This is my working directory for git/GitHub practice

**Git** - is a distributed version control system that tracks changes in any set of computer files.

*Git* works on the local machine and can be used without connection to a server. It is a file storage

**GitHub** - is a hosting service for software development and version control using Git. It provides the distributed version control of Git plus access control, bug tracking, software feature requests, task management, continuous integration, and wikis for every project.

*GitHub* - is a cloud server that stores version control of the file

* 4 STAGES :*
- Working directory : run ``git init`` to initialize the working directory as a repository, ***.git*** folder will be created . If you delete this directory ,  repository will become  a simple folder.

- Staging area : ``git add .`` 

- Local repo : local folder : ``git commit -m “message” or -am “message ”``

- Remote repo : ``git push origin main``

To clone a repository from GitHub run ``git clone andCopyTheSSHurlFromTheGithub``
When multiple people in the team work with the same repository and modify files , run ``git pull`` - to  download the latest updates of the file (latest version)

To upload updates from your local repo to remote , run ``git push`` command

``git checkout -b "my_new_branch"`` -to create and switch to a new branch
``git branch branchname`` - just to create a new branch 
To switch to new branch : ``git checkout nameofthebranch``

``git branch`` - to check the list of branches
``git branch --delete my_new_branch`` -  to manually delete branch from git

``git status`` - to check your current branch and commits
``git fetch`` - works like *git status* but for the remote GitHub repository

## .gitignore
Not trackable content of the file . Add files to .gitignore to make these files hidden , content of these files will be available only in your local git but not on the GitHub.
