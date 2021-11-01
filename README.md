# Initializaing Git For Version Control

# Step 1
# Add your name and email then paste on ternimal
* git config --global user.name "Your Name"
* git config --global user.email "Your Email"
* git config --global push.default matching
* git config --global alias.co checkout

# Step 2
# Create git folder
* git init
* git branch -M master
* git add README.md
* git commit -m "initial commit"

# Step 3 ( this step is connecting your github with your termimal without always check your password and id, is a must )
# Generate ssh key -->
* ssh-keygen -o
# Save into /root/.ssh/id_rsa
*** Note: no password added, else it git access will keep asking password everytime
# Show and copy ssh key
* cat /root/.ssh/id_rsa.pub

# Step 4
*** Note: go github settings, SSH and GPG keys, and add new SSH keygen

# Step 5
*** Note: create new Repository

# Step 6 …or push an existing repository from the command line
# Select ssh
* git remote add origin git@github.com:differentMonster/my-github.git
* git branch -M master
# Need to " add . "  and " commit -m " before pushing to github
* git push -u origin master
