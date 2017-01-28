make updates on gh-pages:
git checkout gh-pages
git pull
git add .
git commit -m ""
git push

Merge to Master:
git checkout master
git pull origin master
git merge gh-pages
git push origin master