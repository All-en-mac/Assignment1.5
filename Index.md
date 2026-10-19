1 & 2. Create a GitHub Account and Repository
Go to GitHub and log in (or create an account if you haven't already).

Click the + icon in the top right corner and select New repository.

Name your repository (e.g., web-development-practice).

Choose Public.

Important: Do not check the boxes to add a README, .gitignore, or license (since you already have a local repository with existing files).

Click Create repository.

3. Connect Your Local Repository to GitHub
Open your terminal inside your project folder (web-development-practice) where you initialized Git in the previous assignment, and run the commands provided by GitHub (replace the URL with your actual repository URL):

Bash
# Set the main branch name (if not already set)
git branch -M main

# Link your local repository to the remote GitHub repository
git remote add origin https://github.com/YOUR-USERNAME/web-development-practice.git
4. Upload Files Using git push
Push your existing commits up to GitHub for the first time:

Bash
git push -u origin main
5. Add a New File and Push a Second Commit
To fulfill the requirement of adding a new file and pushing an update:

Create a new file (for example, a README.md file):

Bash
echo "# Web Development Practice\nMy practice projects for week 1." > README.md
Stage and commit the new file locally:

Bash
git add README.md
git commit -m "docs: add README.md with project description"
Push the new commit to GitHub:

Bash
git push
6. Verify on GitHub
Open your repository page in your web browser.

Click on the Commits tab (or check the file list) to verify that your new commit history is visible online.

Submission
Copy the public URL of your GitHub repository (e.g., [https://github.com/YOUR-USERNAME/web-development-practice](https://github.com/YOUR-USERNAME/web-development-practice)) and submit it as required!