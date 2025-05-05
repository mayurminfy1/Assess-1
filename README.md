# Git Fundamentals & GitHub Collaboration

## Assignment 1: Fundamental Git Commands and Workflow

### Objective
Learn fundamental Git commands and their basic workflow.

### Explanation of Git Commands

1. **Initialize a Local Git Repository**  
   - Used `git init` to initialize an empty Git repository in the project directory.  
   - This creates a `.git` folder, allowing version control for the files in the directory.

2. **Create and Add a File to Staging**  
   - Created `sample.txt` using `touch sample.txt`.  
   - Added initial content to the file and staged it with `git add .`.  
   - Committed the changes using `git commit -m "first"`, creating the first commit in the repository.

3. **Making Changes and Committing Updates**  
   - **First Change:** Added a new line using `echo "Rafting is best at Rishikesh" >> sample.txt`.  
     - Staged and committed with `git commit -m "Line Added"`.  
   - **Second Change:** Updated an existing line using `sed -i 's/I work at Minfy Tech./I work at Minfy Technologies/' sample.txt`.  
     - Staged and committed with `git commit -m "Line 2 updated"`.  
   - **Third Change:** Removed a line and committed using `git commit -m "Line 3 removed"`.  

4. **Viewing Commit History**  
   - Used `git log --oneline --graph` to display a concise history of commits.  
   ![Git Log Screenshot](https://github.com/mayurminfy1/Assess-1/blob/main/Git%20log.png?raw=true)  

5. **Examining Differences Between Commits**  
   - Used `git diff HEAD~1 HEAD` to compare the latest commit with the previous one.  
   ![Git Diff Screenshot](https://github.com/mayurminfy1/Assess-1/blob/main/Git%20diff.png?raw=true)  

---

## Assignment 2: GitHub Basics & Collaboration

### Explanation of GitHub Commands

1. **Push Repository to GitHub**  
   - Added a remote repository using `git remote add origin https://github.com/mayurminfy1/Assess-1.git`.  
   - Set the main branch using `git branch -M main`.  
   - Pushed changes to GitHub with `git push -u origin main`.  

2. **Pull Changes from GitHub**  
   - Used `git pull origin main` to ensure the local repository is in sync with GitHub.  

3. **Create and Work on a New Branch**  
   - Created a branch for updating the README file using `git branch update-readme`.  
   - Switched to the new branch using `git checkout update-readme`.  
   - Made changes and committed them with `git commit -m "Readme updated on branch"`.  
   - Pushed changes to GitHub using `git push origin update-readme`.  

4. **Creating a Pull Request and Merging**  
   - Opened a pull request from `update-readme` to `main` on GitHub.  
   - Reviewed and merged the pull request.  
   ![Pull Request Merge Screenshot](https://github.com/mayurminfy1/Assess-1/blob/main/pull%20request%20merged.png?raw=true)
![Pull Request Merge Screenshot](https://github.com/mayurminfy1/Assess-1/blob/main/merge%20pull%20ss.png?raw=true)


---

## Summary of Commit Changes  

1. **First Commit:** Added initial file with basic information.  
2. **Second Commit:** Added a sentence about rafting.  
3. **Third Commit:** Corrected formatting of company name.  
4. **Fourth Commit:** Removed unnecessary content.  

---
