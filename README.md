# PLPBasicGitAssignment
# Local Folder Setup
mkdir PLPBasicGitAssignment
cd PLPBasicGitAssignment

# Git Initialization
git init

# Connecting to GitHub
git remote add origin https://github.com/brayan-root/PLPBasicGitAssignment.git

# Creating a File
echo "Hello, Git!" > hello.txt

# Staging Changes
git add hello.txt

# Committing Changes
git commit -m "Add hello.txt with a greeting"

# Pushing to GitHub
git push -u origin main
