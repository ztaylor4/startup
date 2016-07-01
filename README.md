##What is Version Control?
 - backup
 - teamwork
 - sharing

##Other Version Control
 - Mercurial
 - SVN

Really just worry about git

##Git topics

Branches and forks

git clone
: get a local copy of a remote repository

git init
: start a repository

.gitignore
: the file listing files not to add to the repo automatically

git add
: add a file to be tracked in your repository

git commit
: save a change or set of changes into a pushable bundle

git checkout -b
: create a new branch

git checkout
: change from one branch to another

git push
: send your changes to a remote repository

git rebase
: add changes from one branch to another

git rebase -i
: how to deal with incompatible merges

##Other links

[Git Koans](http://stevelosh.com/blog/2013/04/git-koans/)

[Generating SSH keys](https://help.github.com/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent/)

    ssh-keygen -t rsa -b 4096 -C "your_email@example.com"
    ssh-add ~/.ssh/id_rsa