# TCN-Website

The aim is to build a learning management system (LMS) to help young people who love tech access information easily

# Create a branch:

kindly create a branch for your work and push to that
branch. The mainter will merge each pull request after
confirming the request will not 'scatter' other code.

# For central pull:

You can change directory to the main/master branch to
git pull an updated version of the website from time to
time.

# To start, run these code:

Using HTTP:
git clone https://github.com/fay22ekanem/TCN-Website.git

Using SSH:
git clone git@github.com:fay22ekanem/TCN-Website.git

cd into the directory TCN-Website and run these codes:

git init

git add .

git commit -m "add what you did"

git remote add origin git@github.com:fay22ekanem/TCN-Website.git

or

git remote add origin https://github.com/fay22ekanem/TCN-Website.git

git branch -m main

git push -u origin main

# 3 ways to check branch in git:

Type Command  
Local branches:

git branch

Remote branches:

git branch -r

All branches:

git branch -a

# Steps to create a branch:

1. Create and Switch to the New Branch (Most Common)

    git checkout -b <new-branch-name>

Example:

git checkout -b feature/user-authentication

2. Create the Branch Without Switching to It

    git branch <new-branch-name>

Example:

git branch experiment

git checkout experiment

# To push from your branch:

git push --set-upstream origin [your branch name]

# In case your branch is ahead of the main branch:

Click the contribute button on github website and enable pull request.

This will be seen by the code maintainer and accept your

request after confirming there is no error.

# In case main branch is ahead of your branch:

run: git pull from your branch

# To restrict push conflit:

@fay22ekanem kindly go to

settings --> Branches --> Add neccessary restrictions
under Branch protection rules

kindly delete line 69 to 76 when you are done
