## Introduction Of Git
  - git is a version control system where the repository stored on server.it helps to work togher
## Git Commands
  - `git init` - to create empty repository
  - `git status` - current status git tree
  - `git diff` - it show modified files before commit
  - `git show` - it show the history of git
  - `git checkout` -to recover or to switch the branch
  - `git merge` - to merge the branch
  - `git fatch` - it fetch the remote server files to local server
  - `git push` - it uses to upload the local repo to remote
  - `git clone` - it clone the repository to local server
  - `git branch` - it shows all present branches
  - `git add `- it saved the files


## Getting Start With Git
 - step 1
   make repository
    - ```
          git init 
                     
 - step 2
   create a file
    - ```
         git touch hello1
         
 - step 3
   save the files
    - ```
          git add
          
 - step 4
   write something inside file 
    - ```
           git cat>hello1
           
           hi 
           how are you 
           
 - step 5
   check status file added are not 
      - ```
           git status
           
 - step 6
   for commit
     - ``` 
          git commit -m"comment"

 - step 7
 -  for push
     - ```
           git push origin master 
           

### For merging file
   - ```
          git pull origin master (load the file from remote)
          git branch
          git merge master
          git push origin sushil
          
          
    ``` 
      to save current and go to another directory (another activity)
      git stash   (saved current working directory)
      git stash pop  (back to directory where puase)
         
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
