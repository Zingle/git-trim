This package installs the `git trim` command.  This command can be used to
trim your local repository of any merged branches.

Install
=======
```sh
sudo -H npm install -g @zingle/git-trim
```

Use
===
```sh
# enter git repo directory
git trim master                 # trim branches not merged into master
```
