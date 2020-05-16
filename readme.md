## GitHub command cheatsheet for MacOS terminal
Create a new repository
``` bash
mkdir <repoName>
cd <repoName>
git init
echo readme > readme.md
git add .
git commit -m "type_comment_here"
curl -u "<your_username>" https:api.github.com/user/repos -d '{"name": "<repoName"}
```
