Hi Hashers….

Here I present you the GIT Assignment-

Task-1
To configure password-less authentication in git

Create Personal Access Token from github 
Generate and Copy Token
Paste in <repo-dir>/.git/conf , between the https://------<token>-----@github.com/<username>/<repo-name>


Task-2
To create the repository with name “hu_devops_19”

Task-3
Clone the repo to the localhost
  
 $git clone <repo-link>

Task-4
To create a branch name git-assignment

$git checkout -b git-assignment

Task-5
To create secret file on the branch locally and it should not push to the remote repo while executing push commands
  - Added the secrets in .gitignore file
  - git add . 
  - git commit 
  - git push

Task-6
To create SECURITY.md file and enter the information about secrets 

Task-7
Create the README.md file and mention all the steps that you have performed.

Task-8
Clone the repo and delete the HEAD commit from it.
  - git reset --hard HEAD~1

Task-9
Create a new branch from a specific commit id
  - git branch <branch-name> <commit-id>


