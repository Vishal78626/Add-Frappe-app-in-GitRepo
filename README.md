# Steps to push your Frappe app on Github using terminal

1. First go to location where all apps are installed.
2. Go to the app directory which you want to push.
3. Creating new Repository on Github using terminal.
```
curl -u "GitProfileName" https://api.github.com/user/repos -d '{"name":"Noticeboard_GNEEDU","public":true}'
```
4. Check it on github a new repository is created.
5. Creates a new branch and also switches to it, -b initialize branch.
```
git init -b main
```
6. Select all files & folder inside the directory.
```
git add .
```
7. Records or snapshots the file permanently in the version history.
```
git commit -m "first commit"
```
8. -M --move --force.
```
git branch -M main
```
9. Always Use HTTPS(easier & faster than other) path otherwise you have to setup SSH setting in your github profile.
```
git remote add origin "path"
```
10. After hit enter add Github username & Password then your files successfully added in your Repository.
```
git push -u origin main
```


Note: (Now github uses personal access tokens as a password. To generate personal access tokens Goto your profile settings/Developer settings/Personal access tokens Generate token).
