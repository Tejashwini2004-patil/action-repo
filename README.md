# Create a local repo
mkdir action-repo && cd action-repo
git init

# Create a README
echo "# Action Repo" > README.md

# Push to GitHub
git add .
git commit -m "Initial commit"
git remote add origin https://github.com/Tejashwini2004-patil/action-repo.git
git push -u origin master

