My first python django application

Create folder locally with your app name Add Python and Django linter to VS Code: VS Code > Extensions > Find & Install (Python by Microsoft, Django by Baptiste Darthenay, Auto Close Tag by Jun Han)

Open git bash in this folder

git init - initialize repozitory locally

Create new public repo on github, adding README and .gitignore template - python

Copy repository address (code / https > link https://my-repo-link.git)

In git bash link local repo to remote origin:

git remote add origin https://my-repo-link.git git branch -M main git branch --set-upstream-to=origin/main main

Install Django framework: pip install django --upgrade

Follow tutorial part 1: https://docs.djangoproject.com/pl/5.0/intro/tutorial01/#top

additional tutek: https://www.scaler.com/topics/add-css-file-to-django/