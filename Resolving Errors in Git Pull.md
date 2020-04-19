# Handling errors when interacting with a remote repository
- fatal: refusing to merge unrelated histories

# fatal: refusing to merge unrelated histories

  The error is resolved by toggling the allow-unrelated-histories switch. After a git pull or git merge command, add the following tag:

  ```sh
      $ git pull origin master --allow-unrelated-histories
  ```
