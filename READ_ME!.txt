This a simple exemplo how to use the github from the command terminal.

The more important command is in the list belown;

git clone <repository url>    --> This will download the repository to your computer.

ls                            -->  Is a command that lists all files and folders in your current directory

cd <repository name>           -->  To change directory into that folder

touch <new file name>          -->  To create a new file in that folder

git add <new file name>        -->  To let Git know that it should be keeping track of the new file you’ve made this command is to track that specific file

git add --> To track all files within that directory.

git commit -m "some message"   -->  Commit those change and describes the changes you just made

git status                     -->  To see how our code compares to the code on the remote repository

git push                       --> To publish

Potentially even more helpful, if you realize that you’ve made a mistake, you can revert back to a previous commit using the command git reset in one of two ways:

git reset --hard <commit>      --> reverts your code to exactly how it was after the specified commit. To specify the commit, use the commit hash associated with a commit which can be found using git log as shown above.
git reset --hard origin/master --> reverts your code to the version currently stored online on Github.

git branch                         --> Implement branching in our git repositories

git checkout -b <new branch name>  --> To make a new branch

git checkout <branch name>         --> Commit any changes to each branch 

When we’re ready to merge our two branches together, we’ll check out the branch we wish to keep (almost always the master branch) and then run the command 
git merge <other branch name>      -->  This will be treated similarly to a push or pull, and merge conflicts may appear.

Forking: As a GitHub user, you have the ability to fork any repository that you have access to, which creates a copy of the repository that you are the owner of. We do this by clicking the “Fork” button in the top-right.