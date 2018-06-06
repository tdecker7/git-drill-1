  555  git init
  556  touch readme.md index.html style.css
  557  git remote add origin git@github.com:tdecker7/git-drill-1.git
  558  git add index.html
  559  git status
  560  git commit -m "added index.html"
  561  vi readme.md
  562  git add -A
  563  git reset
  564  touch app.js
  565  mv ~/Downloads/vitas.gif .
  566  git add -A
  567  git commit -m "Galvanize got me like..."
  568  git log
  569  git push origin master
