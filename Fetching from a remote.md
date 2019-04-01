# Useful commands when interacting with a remote repository
  - git clone
  - git fetch
  - git merge
  - git pull

# Clone 
To grab a complete copy of another user's repository
```sh
    $ git clone https://github.com/USERNAME/REPOSITORY.git
```
# Fetch
Use git fetch to retrieve new work done by other people without merging those changes into your own branches.
```sh
    $ git fetch remotename
```
# Merge
Merging combines your local changes with changes made by others.
Typically, you'd merge a remote-tracking branch (i.e., a branch fetched from a remote repository) with your local branch
```sh
    $ git merge remotename/branchname
```
# Pull
Grabs all online updates and merges them with your local work
git pull equals git fetch and git mergein the same command
```sh
    $ git merge remotename/branchname
```

# git merge --abort
If you run intoa merge conflict you cannot resolve, or if you decide to quit the merge, you can use the abort flag to take the branch back where it was in before you pulled.
```sh
    $ git merge --abort
```
