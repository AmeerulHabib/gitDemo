# gitDemo
Explore the use of git pull and push request

# setup git config
git config --global user.name "UserName"
git config --global user.email "github@email.com"
git config --list

# enter file directory of the program
mkdir <src>
cd <src>

# initialize
git init
# to check the status of git (either push, pull etc)
git status
###### to pull the changes from the github the current folder ######
git pull <https:/github.com/examaple.git>

###### process of commit ######
# Create file
# Check the status

# Stage the file
git add .
git add <example.txt>

# Commit the file
git commit -m "<updates on the changes>"

# Check the status

# Viewing commit history
git log

###### connect with github ######
git remote add origin github <repo>
git remote -v

###### to push the changes into github ######
git push -u origin main


# IMPORTANT #

When push the changes, if encounter password request, generate and copy the token from the "profile settings > Developper Settings > Personal access tokens > Tokens (classic) > generate token"