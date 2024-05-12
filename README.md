# Create a repository
$ gh repo create project-name --public
(--public, --private, or --internal)

# Commit your first change
## Create a README file with some information about the project.
$ echo "info about this project" >> README.md
$ git status (to check you have untracked README.md file)
$ git add README.md && git commit -m "Add README" (Commit README.md file)
$ git push --set-upstream origin HEAD 

# Cloning a repository
$ gh repo clone REPOSITORY
# You can also use the GitHub URL to clone a repository.
$ gh repo clone https://github.com/PATH-TO/REPOSITORY

# Create a new branch
$ git branch <branch-name>
## Switch to the new branch
$ git checkout <branch-name>
## Merge the branch back into the main branch
$ git merge <branch-name>

# Update your local branch
$ git pull