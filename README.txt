Hello Git and GitHub

- create project folder on local computer
- add a readme.txt and other files there

initiate git project
- git init

add the local files to the git project
- git add filename
for all changes, add the files again  (for each file separately)

check git project status:
- git status

commit all changes to the git project
- git commit -m "descriptive comment about the changes"


connect local git project:
- set up a new repository in the online git platform ( for easier overview, name it as the local project folder)
- set it to private
- create repository

connect the local git project to the online repository
- push an existing repositoryfrom the command line:
- git remote add origin https://github.com/pia-pia/repositoryname.git
- git branch -M main
- git push -u origin main

- add git hub user credentialts
- if password is not working, create an OAuth token:
https://docs.github.com/en/github/authenticating-to-github/creating-a-personal-access-token



synchronize local code in git project with git online repository
- check if all changes are committed
- git status (should be empty)
- git push -u origin main
