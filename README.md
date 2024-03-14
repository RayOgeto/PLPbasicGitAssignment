
### Task 1: Repository Setup

1. **GitHub Repository Creation:**
   - Logged in to GitHub account.
   - Created a new repository named "PLPBasicGitAssignment".
   - Initialized with a README file.

### Task 2: Local Setup

2. **Local Folder Setup:**
   - Created a new folder named "PLPBasicGitAssignment" on the local machine.

3. **Git Initialization:**
   - Initialized a new Git repository in the local folder.
   - Command used:
     ```bash
     git init
     ```

4. **Connecting to GitHub:**
   - Linked the local repository to the GitHub repository.
   - Command used:
     ```bash
     git remote add origin <repository-url>
     ```

### Task 3: Making Changes

5. **Create a File:**
   - Created a new text file named `hello.txt` inside the local folder.
   - Added the text "Hello, Git!" to `hello.txt`.

6. **Committing Changes:**
   - Staged the changes.
     ```bash
     git add hello.txt
     ```
   - Committed the changes.
     ```bash
     git commit -m "Add hello.txt with a greeting"
     ```

### Task 4: Pushing to GitHub

7. **Pushing to GitHub:**
   - Pushed the committed changes to the GitHub repository.
     ```bash
     git push -u origin main
     ```

### Task 5: Verification

8. **Verified on GitHub:**
   - Visited the GitHub repository in a web browser to confirm the visibility of `hello.txt` and the commit message.
