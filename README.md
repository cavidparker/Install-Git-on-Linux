## Install-Git-on-Linux:

$ sudo apt-get update

$ sudo apt-get install git

$ git --version

$ git config --global user.name "your name"

$ git config --global user.email "youremail@gmail.com"


## Crate branch on your git

$ git checkout -b your_branch_name

$ git add .

$ git commit -am "Commit Name"

$ git push -u origin your_branch_name

## Add multiple branch:

$ git branch

$ git checkout Your_branch_name

## git reset 

$ git reset --hard

## git delete 

$ rm -rf .git

# Git PUSH DJANGO ON HEROKU :
- git add .
- git commit -m "commit name"
- git push heroku master
- heroku run python manage.py makemigrations
- heroku run python manage.py migrate
- heroku run python manage.py createsuperuser
- heroku open 





