# Steps to push your Frappe app on Github using terminal

1. First go to location where all apps are installed.
2. Go to the app directory which you want to push.
3. $ curl -u "GitProfileName" https://api.github.com/user/repos -d '{"name":"Noticeboard_GNEEDU","public":true}' (Creating new Repository on Github using terminal).
4. Check it on github a new repository is created.
5. $ git init -b main (This command creates a new branch and also switches to it, -b initialize branch).
6. $ git add . (select all files & folder inside the directory).
7. $ git commit -m "first commit" (This command records or snapshots the file permanently in the version history.)
8. $ git branch -M main (-M --move --force).
9. $ git remote add origin "path" (Always Use HTTPS(easier & faster than other) path otherwise you have to setup SSH setting in your github profile).
10 $ git push -u origin main (After hit enter add Github username & Password then your files successfully added in your Repository).

Note: (Now github uses personal access tokens as a password. To generate personal access tokens Goto your profile settings/Developer settings/Personal access tokens Generate token).
