#             **Git instruction**

## *Git description* 

* Git its a version control system software.
* This tool for tracking and control changes to files. 
* Preferably used with code. But can be used with other types of files. Pictures forexample.


## *New repository creation*
* Create a folger with project.
* Add folger to workspace.
* Use:

      git init


## *Actual condition test for repository*
* For dispaying state of repo use:
              
      git status

## *Adding files from working foldger*
* For adding new file to repository and for tracking before commit use:
         
      git add <File name>

## *Saving changes to **local** repository*
* For saving changes and opening default text editor  to create the commit message. Changes will be saved in local repo only. 
* Use (after **git add**):

         
      git commit

* For entering commit message  in terminal directly:
* Use (after **git add**):

       git commit - m <message>

* For use two commands at once **git add** & **git commit - m**:
        
        git commit - am <message>

* To getting difference between git branches: 
  
      git diff

* For compare commit hashes use:
  
      git diff <hash 1> < hash 2>
      