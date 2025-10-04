# my-first-repo
# Configure Git
git config --global user.name "kartik gupta"
git config --global user.email "kartikg07@example.com"

# Initialize repo
mkdir my-first-repo
cd my-first-repo
git init

# Add a file
echo "# My First Repo" > README.md
git add README.md
git commit -m "first commit"

# Connect to GitHub (replace URL with your repo link)
git remote add origin https://github.com/username/my-first-repo.git
git push -u origin master
