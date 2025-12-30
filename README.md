# CLI (command Line Interface) commands

- Tell your computer what to do
- Commands
- ls -> lists out the contents of the current directory
- cd [directory name] -> change the directory
    - .. -> goes up on directory
    - / -> separate navigating multiple directories
- mkdir [directory name] -> makes a new dirctory
- touch [file name] -> create a file
-mv and rm -> moving and removing a file {I recommend doing this in the explorer bar} never use rm.
- code [directory name] -> open VS Code
    - . -> refers to the current directory
    -  && -> do one command after another finishes
- Flags
    - Extensions of the command
    - Example: ls -a (shows all files and directories in the current folder)

# Git vs Github

    - Git -> version control system using git commands that keeps track of the history of files and folders
    -GitHub -> place to store your projects (also known as a repository)

    Git commands
        -Git init -> allows a project to use git commands
        - Git Status -> shows what has been added/changed/deleted since the last commit
        - Git Add [file name] -> moves files/folders to the staging area
        - Git Commit -> takes everything from the staging area and makes it permanent
        - -m "message" -> shortcut for writing a message on your commit
    - git remote -> another location
        -add -> add connection
        - nickname -> name of the connection (most commonly origin)
        - location -> where is the actual connection
    - git push -> sends your code somewhere
        - nickname -> nickname of the place you want to send your code to
        - branch name -> which branch do you want to push

3 stages
    - working directory (red)
    - staging area (green)
    - project 