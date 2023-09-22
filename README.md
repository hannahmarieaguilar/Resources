# Resources
Resources based on my lab work!

# Relationship Between Nano/VIM/VSCode, Script Files, + Different Programming Languages 

- You can use Nano/VIM/VSCode to write script files
    - nano (exit using ^X)
    - VIM (exit using :q!)
    - VSCode (just make a test file)
 
      
&#8595;



- You can use script files to write the code you want to execute. Using script files is important for saving as well as sharing information.
  - once you pick nano/VIM/VSCode you will write a script file in them

|Examples | Extension|
|--------|------------|
| Bash | .sh|
| Python | .py|
|R | .r|
|yaml | .yaml|
|snakemake | .smk|

Note: extensions are indicators of what language the script should be written in, but this is not always the case. 



&#8595;



- You can use different programming languages depending on what you need to do and how efficiently the program can compute that task.
    - R (can be used for beautiful visualizations (ggplot) and statistics (dplyr))
    - Python (good for parsing and building tables (Pandas))
    - Rust
    - Julia
    - C/C++
    - Java/JavaScript


# Git Commands 

- **git init** will create a new local repository for you
- **git add** will add one or more files to staging
- **git commit -m 'message'** commits changes to the repository
- **git status** tells you what branch you are currently on and whether you have changes to commit or not
- **git clone** allows you to clone a repository into the directory you are currently in (both in Git and local)
- **git remote add origin** or **git remote set-url origin** are used to detail the URL of the remote repository
- **git remote -v** lets you list the current remote repository you are using
- **git push** uploads your committed changes to your remote repository
- **git branch** lists all available branches on your repo and tells you what branch you are currently on. If you want to create a branch, you just have to add the new branch name as a parameter like *git branch <branch name>*
- **git checkout** mores you from one branch to another. It takes your destination branch as a parameter
      - Ex: git check out newBranch//output switches to branch 'newBranch'
- **git pull** pulls the code from your remote repository and combines it with your local repository
- **git diff** allows you to view differences between the branches you are currently in and another
- **git merge** merges the branch you are currently in with another. *Changes* will be incorporated only to the branch you are currently in and not to the other one
- **git log** lists all previous commits you have done in the repository
- **--help** 
