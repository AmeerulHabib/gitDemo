# gitDemo
Explore the use of git pull and push request

# setup git config
git config --global user.name "UserName" <br>
git config --global user.email "github@email.com" <br>
git config --list <br>

# enter file directory of the program
mkdir src <br>
cd src <br>

##### initialize #####
git init

# process of commit 
<b>create/pull, status, make changes, stage, commit, status, push</b>

# To pull the changes from the github the current folder (if want to make changes to current repo)
git pull https:/github.com/examaple.git

# Create file
nano example.txt

# Check the status (to see no changes have been created)
git status

# Stage the file
git add . <br>
git add example.txt <br>

# Commit the file
git commit -m "updates on the changes" <br>

# Check the status (to see the new change)
git status

# Viewing commit history
git log

# connect with github online 
git remote add origin github <repo>
git remote -v

# to push the changes into github 
git push -u origin main

# Done
can see the update in the github

# IMPORTANT 

When push the changes, if encounter password request, generate and copy the token from the "profile settings > Developper Settings > Personal access tokens > Tokens (classic) > generate token"