# neurolab-flask

![image](https://user-images.githubusercontent.com/115451707/196919992-edcfea8b-e3f6-4f35-9398-43be66b5622d.png)


To run flask application 

```
python app.py
```


To access your flask application open new tab in and paste the url:
```
https://{your_url}.ineuron.app:5000/
```

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
git remote rm origin

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