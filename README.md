# Giving $10

## GitHub Pages
https://teamextension.github.io/giving10.github.io

## Run on Local Windows
run.bat
http://127.0.0.1:4000

## Initial Setup for deployment to gh-pages
Checkout your branch, where your build-source is located (maybe src, or master)
(Optional: Add _site to your .gitconfig, so it get's ignored, if not already done)

Remove all content of the _site directory:

> $ rm -r _site/*

Clone your repo's gh-pages branch into the _site directory:

> $ git clone -b gh-pages `git config remote.origin.url` _site

Final steps: Just let jekyll build, do commit & push:

> $ jekyll build

cd into _site:

> $ cd _site,

target all files for commit:

> $ git add -A,

commit them:

> git commit -am 'commit msg'

and push your site to GitHub-Pages:

> git push

