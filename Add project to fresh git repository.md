# A new repo from scratch
  -  Create a directory to contain the project.
  -  Go into the new directory.
  -  Type git init.
  -  Write some code.
  -  Type git add to add the files (add all files using command git add .)
  -  Save in local disk with Type git commit -m "First commit"

# Connect it to github
  - Go to github.
  - Log in to your account.
  - Click the new repository button in the top-right. 
  - Click the “Create repository” button. (add README.md if you like)

# Push project files to repository
  - Sets the new remote
  - Verifies the new remote URL
  - Pushes the changes in your local repository up to the remote repository you specified as the origin
    
       - without ssh
          ```sh
          $ git remote add origin https://github.com/username/new_repo
          $ git remote -v
          $ git push -u origin master
          ```
       - with ssh 
          ```sh
          $ git remote add origin git@github.com:username/
          $ git remote -v
          $ git push -u origin master
         
