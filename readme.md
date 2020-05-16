## GitHub command cheatsheet for MacOS terminal
Create a new repository and connect local to GitHub
```sh
mkdir <repoName>
cd <repoName>
git init
echo readme > readme.md
git add .
git commit -m "type_comment_here"
curl -u "<your_username>" https://api.github.com/user/repos -d '{"name": "<repoName"}
git remote add origin https://github.com/<your_username>/<reponame>
git push -u origin master
```
