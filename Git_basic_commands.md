# Git basic commands 

### Linking the Local and Remote Repository
`git init`
Sets up a directory to be monitored by Git

`git remote add origin `

## Communicating to Git

HTTPS

SSH
generating a key
`ssh-keygen -t rsa -C "user@domain.add"`
 Get the key
 `cat ~/.ssh/id rsa.pub`
 
 
 
 Goto to Setting in Github
 ssh keys link
 add ssh key then save
 
Get SSH url 
git remote set-url origin git@github.com:username/repository.git

## Workflow
`touch new_file.txt`
`git add new_file.txt`
`git commit -m 'a new blank file"`

`git push origin master`







###Adding new files to Git

- `git add`     
 adds all new files
- `git add -u`  
 updates tracking for files that changed names or were deleted
- `git add -A`  
 preforms the above two functions in one line

You need to do one of the above before Committing.

###Commit
`git commit -m "message"`
Message should be a useful description of the change you have made

###Push
`git push`
 This updates the Remote repository
 
 ###Branches
 
 `git checkout -b 'branchname'`
 
`git branch `
 Shows which branch you are on
 
 `git checkout master`
 To switch back to the Master branch
 
 
 ###Once you do a Push
 
 Merging changes back into the original
 Pull request
 
 This is a feature of Github
 
 
 