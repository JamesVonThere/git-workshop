# Thoughts about the class (April 30th 2022)
The class was understandable. Although the parts of the class that involved command prompts were a bit hard to follow, which was made worse with the differences between mac and windows. The enthusiasm for the subject definitely help with the understanding of the class as it motivates me to learn the subject. I appreciate the effort you put into this class.

# Notes
We understood a bit more about why we're learning git and we learnt about the history of git.


cmd commands:

cd (no parameters) - display path
cd - change directory
mv - move
rm -rf / - remove
type null - create file
move - move file
del - remove file
cls - clear cmd


Git commands - from the internet and from memory
git config --global user.name - configures the user name.
git init - create new local repository
git clone /path/to/repository create a working copy of a local repository
git clone username@host:/path/to/repository
git add <filename> - adds a file to git
git add . - adds everything to git
git commit - commits changes into git
git commit -a commit any file you've added with git add, and also commit any files you've hanged since then:
git push - send changes to git
git pull - pull changes from git
git status - list the files you've changed and those you still need to add or commit:
git remote add orgin <server> - If you haven't connected your local repository to a remote server, add the server to be able to push to it:
git remove -v - List all currently configured remote repositories
git checkout -b <branchname> - create new branch and switch to it
git checkout <branchname> - switch from one brancfh to another:
git branch - List all the branches in your repo, and also tell you what branch ypou're currently in
git branch -d <branchname> - delete the feature branch
git push origin <branchname> - push the branch to youre remove repository, so others can use it
git push --all origin - push all branches to your remote repository.
git push origin :<branchname> - Delete a branch on your remote repository
git merge <branchname> - Merge a branch into the one that you're currently on
git add <filename> - After you have manually resolved any conficlts, you mark the changed file
git tage 1.0.0 <commitID> - You can use tagging to mark a significant changeset, such as a release
git log - CommitId is the leadding characters of the changeset ID, up to 10,, but must be unique. Get the ID using this.
git push --tags origin - push all tags to remote repository
git checkout -- <filename> - If you mess up, you can replace the changes in your working tree with the last centent in head: Chnages already added to the idnex, as well as new files, will be kept.
git fetch origin - Instead, to drop all your local changes and commits, fetch the latest history from the server aand point your local main branch at it.
git grep "foo ()" Search thew working directory for foo();