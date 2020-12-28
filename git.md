Glossary

Directory - Folder
Terminal or Command Line - Interface for text commands
CLI - Command Line Interface
cd - Change Directory
Code Editor - Text processor for writing code
Repo or Repository - Project, or the place/folder where your project is kept/stored
Git - The way in which files are version controlled
Github - A website to host your repo's online
DVCS - Distributed Version Control System - This is the structure on which Git is based

Git Commands

init - initialize a folder
clone - Bring a repo that is hosted somewhere like Github into a folder on your local machine for the first time
add - Track your files and changes in Git
. - this will commit everything in the current folder
"file name" - this will only commit the named file
commit - Save your files in Git
-m "Your commit message here"
--amend
--reset-author
push - Upload Git commits from your local repo to a remote repo, like Github
origin - remote repo name
master - branch in the remote repo named above
(push -u origin master) will make the default push location
pull - Download changes from a remote repo to an existing repo on your local machine, the opposite of push
config
--global
user.name "Your Name"
user.email you@example.com
status - shows the status of all files in the current folder
remote
add origin remote-repo-location.git
-v - shows the locations on the remote repo
log - shows the log history of commits
branch - shows all branches
-d feature-01-branch-name
checkout -b branch-name-01
diff (branch to compare to) - highlights differences
reset - either plain or with file name to unstage a change

- HEAD - resets back to the previous commit
- HEAD~1 - resets back to the previous but 1 commit
- commit hash - will reset back to the hash specified
- --hard hash - will reset back to the hash specified and will delete everything else after that
