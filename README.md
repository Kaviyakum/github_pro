# github_pro
 Initialize Git (if not done already)
In the project folder, initialize Git:

bash
Copy code
git init
Step 4: Add Files to Staging
Add all files in the folder to the Git staging area:

bash
Copy code
git add .
Step 5: Commit Changes
Create a commit with a descriptive message:

bash
Copy code
git commit -m "Initial commit"
Step 6: Add GitHub Repository as Remote
Link your local project to the GitHub repository using the repository URL you copied:

bash
Copy code
git remote add origin <repository_url>
Step 7: Push to GitHub
Push the project to GitHub:

bash
Copy code
git push -u origin main
If your default branch is named master, replace main with master.

