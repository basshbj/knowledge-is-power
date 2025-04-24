#### Config local repo with remote
```
git config user.name "<username>" 
git config user.email "<email_address>"
git remote set-url origin https://<username>@github.com/basshbj/<repo-name>.git
```

#### Refresh .gitignore
```
git rm -r --cached .
git add.
git commit -m ".gitignore updated"
git push origin
```