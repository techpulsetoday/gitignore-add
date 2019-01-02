# gitignore-add
Adding a .gitignore to an existing repo

First commit any outstanding code changes, and then, run this command:
```sh
git rm -r --cached .
```
This removes everything from theindex, then just run:
```sh
git add .
```
Commit it:
```sh
git commit -m ".gitignore is now working"
```
You can also remove individual files, if you don't want such a drastic approach:
```sh
git rm --cached filename
```
