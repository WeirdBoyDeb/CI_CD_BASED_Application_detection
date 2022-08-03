# CI_CD_BASED_Application_detection




Creating conda Environment
```
conda create -p venv python==3.7 [In git bash]
```
To activate virtual environment
```
conda activate venv/ [In cmd]
```
To install requirments.txt file
```
pip install -r requiements.txt [in cmd]
```
To check git status
```
git status [all git command in cmd]
```
Fetch & push
```
git remote -v
```
To track all the files
```
git add .
```
stage state to origin state push
```
git commit -m "Commited by Sandip on 04/08/22"
```
Set accounts default identity (Name)
```
git config --global user.name "John Doe"
```
Set accounts default identity (email.id)
```
git config --global user.email johndoe@example.com
```
Push to reposetry from origin state
```
git push origin main
```
To setup ci/cd pipeline we need this 3 steps
```
HEROKU_EMAIL=sandeeproy0605@gmail.com
HEROKU_API_KEY=75dc29ba-62cc-4af4-b2b9-fe10bb3c17e2
HEROKU_APP_NAME=cicd-based4application
```