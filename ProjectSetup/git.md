# Git + Github
Date:  1/21/24 

## Setting up SSH Keys 
Overview: 
- Allows for ease of access; no need to enter creditials every single time
- Secure Communication
- auth: access to repo / sign: signing commits
- in order to push, you need to prove that you are the owner of the account; SSH keys allow this 
  
0. About SSH
  - https://docs.github.com/en/authentication/connecting-to-github-with-ssh/about-ssh 

1. Check for existing SSH key

2. Generate a new SSH key
  - https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent

3. Adding a new SSH key tp 
  - https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account

4. About commit Signature Verifivation
- https://docs.github.com/en/authentication/managing-commit-signature-verification/about-commit-signature-verification

## Commands 
The "git remote -v" command is used in Git to view the remote repositories associated with your local repository. It displays the URLs of the remote repositories along with their corresponding fetch and push URLs
``` git remote -v``` 

## Stages of Pushing 

``` git add \\insert name of file ```
- stage your files and changes for a _commit_
- track your files and changes
- If you created a new file within the repo, then Git to track this file to commit
-	note: use '.'  to add all files / otherwise, you can just state the individual files
  - git add . #all files and folders
  -  git add index.html #individual files

``` git commit -m \\insert message here```
