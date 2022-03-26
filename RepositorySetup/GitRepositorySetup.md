#Setting up a repository

###Initializing a new repository
```
cd <path_to_your_existing_code>
git init
git init <project_directory>
git branch -m master main
```
###Cloning an existing repository
```
// Create a repository on your github account
cd <path_to_parent_directory>
git clone <repo_url>
```	
###Saving changes to the repository
```
git add <filename>
git commit -m "<message>"
```	
###Configuration & setup
```
git remote add <remote_name(origin)> <remote_repo_url> // skip this when you cloned
git pull <remote_name(origin)> <local_branch_name(main)>
git push (-u) <remote_name(origin)> <local_branch_name(main)>
```
###After isntalling Git
```
git config --glabal user.name "<name>"
git config --global user.email <email>
```


