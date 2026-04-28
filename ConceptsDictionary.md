# Dictionary of Concepts

## Differentiang:

- Git: Git is the software that version tracks files and folders

- GitHub: GitHub is the backup of all the versions and contains Git

## Conceptual areas

1. Developing area : Folder where my project is developed
The commit message is mandatory and it will force you to write something if we do git commit without a message

2. Staging Area: where we organize files before moving to a permanent location

3. Local repository :.git file, where the git software keeps all the committed versions, each commit is a point in time

# From local to remote

- SSH KEY : A way to securely connect to our remote computer/location/server. We add it to Github in the setting for ssh key

-How to create an empty repository on GitHub: add a new repository on GitHub, dont add any files and follow instructions to connect with local

- How to create a connection between local and remote
git remote add origin <key>

Git push : it will send the changes to the collaborators and to my backup.
Git pull : it will sync changes that my collaborators sent to github or changes done in other instances

To recover a repository cancelled locally but not on github
git clone ssh 

# Alternative history / Branching

Each branch has a specific name, give a meaningful name
It will have an indipendent, alternative timeline. They share a point in time, that is the first commit in the new branch. The main is usually the refined version and people work on branches


