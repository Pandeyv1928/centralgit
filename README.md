…or create a new repository on the command line
echo "# centralgit" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/Pandeyv1928/centralgit.git
git push -u origin main

===============================

…or push an existing repository from the command line
git remote add origin https://github.com/Pandeyv1928/centralgit.git
git branch -M main
git push -u origin main

=============

git pull origin master

==============================

ignore 

Create hidden file .githidden

# git add .gitignore

# git log -1

# git log --oneline

# git log --grep ""
