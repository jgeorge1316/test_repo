# Here is the steps to use this library:
Testing github usage through terminal

## clone github
```sh**
git clone https://github.com/jgeorge1316/test_repo
cd test_repo
```

## setup venv in windows:
Create venv windows:
```sh**
python -m venv env
```

## enter virtual environment in windows
Windows terminal command to activate venv:
```sh**
Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass
env\Scripts\activate
```

## install necessary libraries
```sh**
pip install -r requirements.txt
```

## run test.py 
```sh**
python test.py
```

# using Github
## initialize git in folder
```bash
git init
```

## connect to github repo and check
```bash
git remote add origin your-repo-url
git remote -v
```

## add files
```bash
git add .
```

## commit (with message)
```bash
git commit -m "put message here"
```

## push to github (to main branch of course :) )
```bash
git branch -M main
git push -u origin main
```

## chatgpt chat that helped me:
[link](https://chatgpt.com/share/67bd30cc-1670-800b-ac12-ad7869e22d8b)