# Hello World
Testing github usage through terminal

## setup venv in windows:
Create venv windows:
```
python -m venv env
```
Windows terminal command to activate venv:
```
Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass
env1\Scripts\activate
```

## install necessary libraries
```
pip install -r requirements.txt
```
#using Github
## initialize git in folder
```
git init
```

## connect to github repo and check
```
git remote add origin your-repo-url
git remote -v
```

## add files
```
git add .
```

## commit (with message)
```
git commit -m "Initial commit"
```

## push to github (to main branch of course :))
```
git branch -M main
git push -u origin main
```
