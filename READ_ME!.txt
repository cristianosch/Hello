This a simple exemplo to use the github from terminal of command

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