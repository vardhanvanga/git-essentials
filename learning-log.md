# My Learning Log

## About This Project

I'm learning Git and version control to track my work.

## Goals

- Understand how commits work
- Learn branching and merging
- Push my work to GitHub

## What I Learned Today
- Git is like a time machine for your files
- Every commit is a snapshot you can go back to
- Git tracks changes to files over time
- Branches let you experiment without affecting the main project
- You can merge branches back together when ready

## Commands Used

1. ```git version```

        -- to know the version of git
2. git config commands
    ```
     git config --global user.name "Your Name"
   
     git config --global user.email "your-email@example.com"

     git config --global --list
   ```
3. ```cd "file path"``` -- to move into working directory

4. ```git init ``` -- to make folder into repo and git will create git folder so it track changes in it 
   ```git add learning-log.md ``` -- add files in staging area .

    - '''staging area ''' is the place where files will be places before commit or saving permanently also called index

   ```git commit -m "Add initial learning log" ``` -- it will commit the files with a message .

5. ``` git log```  -- to verify the commits or to check the changes history .

6. ``` git status``` -- to check current status of your repo and 
                        confirm is your working directory is clean by running command.

7. ```git log --oneline``` - to view compact version of commit history.

8. ``` git checkout -b add-resources ```  
    - creates a new branch and moves to that new branch 
9. ``` git branch ``` 
    - it will show the current working branch and remaining branches.

10. ``` git checkout main```
    - to return back to main branch we use this command 

11. ```git merge <branch name>``` 
    - this will merge the given branch into current working brnach 
