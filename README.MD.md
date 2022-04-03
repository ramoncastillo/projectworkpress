My repo 

Step 1: Create a new repository in the version control page
Step 2: Open CLI or terminal
Step 3: Set up local project " directory " as the current working directory 
        -pwd # path verification
        - Move to the directory where the files are located
 
Step 4: Initialize the local repository as a Git Repository
  (I)   -git init
Step 5: Add the files to your new local repository. 
        Files will now be staged for first commit            
  (II)  -git add .  # Add all the file to the folder
        -git status # Check the changes or files ready for commit

Step 6: Commit the files that are in staged in the local repository
  (III)  -git commmit -m "Workpress Project"

Step 7: copy the remote repository's url->https from the version control page
   (IV)   -git remote add origin url
         https://github.com/ramoncastillo/projectworkpress.git

Step 8: copy the remote repository
    (V)  -git push -u origin master \main
         username:
         personal token


Folder PATH listing for volume Windows
C:.
├───files
└───vars

C:\myrepo\projectwordpress>

References:

   How to Push Code to Github.  https://www.codecademy.com


    