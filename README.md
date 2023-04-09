## End to End ML Project


### Created a environment

```
conda create -p venv python==3.8

conda activate venv/
```
### Install all necessary libaries

```
pip install -r requirements.txt

```

### make change in use_subprocess to False
## OPEN C:\Users\iPC\AppData\Local\Programs\Python\Python37-32\Lib\idlelib\pyshell.py and find use_subprocess change it to False from before it is True
```
use_subprocess = False

```

### To PUSH FILE ON GIT REPOSITORY 
```
ls -a

git remote -v
```
## to change ineuron director to your own
```
git init

ls -a

git add .

git status

git commit -m "First commit" 
```
## SET USER.EMAIL AND USER.NAME
```
  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"
```
## CHANGE BRANCH TO MAIN
```
git branch -M main

git remote add origin https://github.com/KanhaiyaKumar-tech/linearRegression.git

git push -u origin main

git status

git remote -v

ls -a
```
## if already done it then do below step
```
git add .
git commit -m "change commit"
git push -u origin main
git status
```
## to create a new branch and change to new branch
```
git branch new-branch-name

git checkout new-branch-name

git add .

git commit -m "commit message"

git push origin new-branch-name

```
### if give remote origin already exists
```
git remote rm origin

git remote -v
```