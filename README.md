# Initialize a new git repository with the main branch
git init -b main

# Add the remote repository URL
git remote add origin https://github.com/Giusstation3/museo_soumaya.git

# Create an empty initial commit with a message
git commit --allow-empty -m "main init"

# Push the main branch to the remote repository
git push -u origin main 

# Create and switch to a new branch named 'readme'
git checkout -b readme 

# Open README.md file in the nvim editor
nvim README.md
    :wq

# Stage the README.md file for commit
git add README.md

# Commit the README.md file with a message
git commit -m "first readme commit"

# Push the readme branch to the remote repository and set upstream
git push -u origin readme

# Enlaces a los pull requests

https://github.com/Giusstation3/museo_soumaya/pull/1



# Enlace a la página Github pages

https://giusstation3.github.io/museo_soumaya/

