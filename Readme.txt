$ git init
$ git remote add origin https://github.com/Simon57050/devweb1-eval-git.git
$ git branch -M master

$ git push -u origin master
error: src refspec master does not match any
error: failed to push some refs to 'https://github.com/Simon57050/devweb1-eval-git.git'

$ git branch
$ git checkout -b master
$ git add .
$ git commit -m "Votre message de commit"
$ git branch -r
$ git push origin master
$ git status
$ git push --set-upstream origin master
$ git branch dev 
$ git checkout dev
$ git add index.html
$ git commit -m "ajout du nouveau fichier"
git push --set-upstream origin dev
