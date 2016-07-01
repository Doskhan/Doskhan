July 1
------

Today I have learned a lot about git.

**Git** allows groups of people to work on the same documents (often code) at the same time, and without stepping on each other's toes. It's a distributed version control system.


<git status> command to see what the current state of our project is:

add it to the staging area by using 'git add'.

To store our staged changes we run the 'commit' command with a message describing what we've changed

'git log' as a journal that remembers all the changes we've committed so far, in the order we committed them. 

This command takes a remote name and a repository URL, which in your case is https://github.com/try-git/try_git.git.

The __name__ of our remote is 'origin' and the __default local branch name__ is master. The '-u' tells Git to remember the parameters, so that next time we can simply run 'git push' and Git will know what to do. 

'git diff' command look at what is different from our last commit

In this case we want the diff of our most recent commit, which we can refer to using the HEAD pointer.

'git diff' with the --staged option to see the changes you just staged. 

You can unstage files by using the 'git reset' command

Files can be changed back to how they were at the last commit by using the command: 'git checkout -- <target>'.

using the 'git rm' command which will not only remove the actual files from disk, but will also stage the removal of the files for us.

'git merge' merge your changes

You can use 'git branch -d <branch name>' to delete a branch.
