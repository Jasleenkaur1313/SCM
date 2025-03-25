# Understanding .gitignore in Git

##  What is .gitignore? 
A .gitignore file is used in Git to specify which files or directories should be ignored and not tracked by Git. This is useful for keeping unnecessary, temporary, or sensitive files out of your repository.

##  Why Use .gitignore? 
- Prevents unnecessary files (logs, temporary files) from being committed.  
- Avoids committing sensitive data (API keys, passwords).
- Improves project organization by keeping repositories clean.  

##   How to Create a .gitignore File  
###  Method 1: Create Manually  
1. Open your project folder.  
2. Create a new file named .gitignore.  
3. Open it in a text editor and add patterns to exclude files.  

###  Method 2: Use Git Command  
Run the following command:  
```bash
touch .gitignore

