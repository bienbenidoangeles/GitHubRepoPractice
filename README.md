# Intro to GitHub 
## Practice Practice Practice
6.3 9/24     Class notes

### Soft Notes--
Resilience + grit = growth mindset
Resilience = determination to persevere
Grit = determination to complete something for the long haul

### Tech notes--
GitHub - distribution version control system
Repository - a folder that monitors your files
Open source - public code available to everyone
Xcode - IDE (Integrated Development Environment)
GUI (Graphic User Interface)
Terminal: CLI - Command Line Interface
VI (Visual Editor) - CLI Shipped with terminal; two modes of use command/edit insert mode, COMMAND MODE: esc key, INSERT MODE: “I” key
Forking - to clone an original copy of a repository
Commit - commits to this master branch
Pull request - request to make 

### Terminal Commands--
pwd -present working directory
Clear - clears text
Cd - change directory, Cd ~/Desktop - change directory to desktop
Ls - list connects of current directory 
Touch “filename” - create a file, “” not needed
Open “filename” - open a file
Mkdir “directory” - create a folder
Echo - gives terminal a command, echo “text message” >> terminal.txt - paste text message to terminal.txt
Rm “filename” - deletes files
Rm -rf “directory” - deletes directory
vi “editor” - creates a editor, if in command mode type “I” to go to insert mode, if in insert mode the esc key goes to command mode. :w - saves file :wq - save and quit
Cd .. - change back to previous directory 

### GitHub Commands—
-ON TERMINAL-
Git - command to interact with files on GitHub, get Clone “repo url"
Git status - states modifications to files
Git add . - add all modified files to be ready, git add “file” - to add specific file
Git commit - commit files to be ready to be pushed out to git repo, git commit -m “message that explains your commit"
Git push - push and “add” files to git repo on GitHub
Git init - initializes a repository on GitHub from current Directory
Git log - shows history

### How to push local repo to GitHub-
Mkdir “folder”
Cd “folder"
Touch “file"
Git init
Git status
Git add  “file”
Git commit -m “string message”
*Create Repo on GitHub.com to get origin link*
git remote add origin “url origin link"
Git push
git push --set-upstream origin master
