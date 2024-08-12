requirements
GitHub Account: Create one if you don't have it already.
Git: Installed on your local machine.
Code Editor: Choose one (e.g., Visual Studio Code, Sublime Text).
Task 1: Repository Setup
GitHub Repository Creation:
Log in to your GitHub account.
Create a new repository named PLPBasicGitAssignment.
Initialize the repository with a README file.
Task 2: Local Setup
Local Folder Setup:

Create a new folder on your local machine named PLPBasicGitAssignment.
Open a terminal or command prompt and navigate to this folder.
Git Initialization:

Initialize a new Git repository in your local folder.
bash
Copy code
git init
Connecting to GitHub:

Link your local repository to the GitHub repository you created in Task 1.
bash
Copy code
git remote add origin <repository-url>
Replace <repository-url> with the URL of your GitHub repository.
Task 3: Making Changes
Create a File:

Inside your local folder, create a new text file named hello.txt.
Add a simple text message like "Hello, Git!".
Committing Changes:

Stage the changes.
bash
Copy code
git add hello.txt
Commit the changes with a descriptive message.
bash
Copy code
git commit -m "Add hello.txt with a greeting"
Task 4: Pushing to GitHub
Pushing to GitHub:
Push the committed changes to your GitHub repository.
bash
Copy code
git push -u origin main
Task 5: Verification
Verify on GitHub:
Visit your GitHub repository in a web browser.
Confirm that the hello.txt file and the commit message are visible.
