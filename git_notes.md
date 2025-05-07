  # GIT INTRODUCTION
-----------------------------------------------------------------------------------------------
 Git is a distributed version control system that tracks changes in files and folders in a project over time. It allows multiple 
 developers to work on the same project simultaneously without interfering with each other's progress. Git is known for its efficiency, 
 flexibility, and robust support for branching and merging. 

 ### github and gitlab
  GitHub is a web-based platform used for storing and managing code, particularly for software development. It uses the version control      system Git, which allows multiple people to work on a project together efficiently by tracking changes and enabling collaboration. 

  ## working of git:
  ![ working_of_git](featured.png)
--------------------------------------------------------------------------------------------------------------------------------------
  ## commands in git:
    Before writing the commands to create the directory/folder for converting into git-repository.
    
   ###### 1)git config --global user.name user_name
   ######  git config --global user.email email_name 
         above command show who is the owner of the repository.

   **2) git init**- This command is used to convert folder into git repository.<br/>
   **3) git status**-This command is used to check the statyus of the file.<br/>
   **4) git add**- This command is used to add the files in staging area.
           *git add file_name*-this add a particular file in staging area.
           *git add .*- This command is add all the files in staging area.
   **5) git commit**-This command is used to add the files from staging area to local area.
          *command: git commit -m "pass any commit*
   **6) git push**-this command is used to add the files form local repository to remote repository.
            *command for first-time to push local repository into remote repository(github)
                  git push url_of_github_repo --set-upstream branch_name
   **7) alias**- This is used to create the short name for github repository url
            *command: git remote add origin(any_name) url_of_github_repo*
            *To check alias:* use git remote command
   **8) git clone**-This is used for reterive data from remote to local repository for first time.
             *command: git clone url_of_remote_repository
   **9) git pull**-When we want to retrive data from updated remote repository then use git pull command.
             *command-*: git pull url_of_remote_repository
   **10) git diff**-git diff is a command-line tool in Git that shows the differences between various states of a repository. It helps          developers see what changes have been made, whether they are between working directory and the staging area, between the 
        staging area and the last commit, or between any two commits.
            *commands-:* git diff -for changes in working area
    **11)configure list**- git config --list
    
    
    
      
        
   
    
