# machine learning projects

Start Machine Learning Projects

Software and accoutn requirements - 
1. [Github Account] - (https://github.com)
2. [Heroku Account] - (https://dashboard.heroku.com/login)
3. [VS code IDE] - (https://code.visualstudio.com/download)
4. [Git cli] - (https://git-scm.com/downloads)
5. [Git Documentation] - (https://git-scm.com/docs/git)

Creating conda environment
```
conda create -p venv python == 3.11.1 -y
```
```
conda activate venv/
```
OR
```
conda activate venv
```
```
pip install -r requirements.txt
```
> Note: To add a file
```
git add <file_name>
```
> Note: To add all files at a time
```
git add .
```
> Note: To ignore file or folder from git we can write name of file/folder in .gitignore file

To check the git status
```
git status
```
To check all version maintained by git
```
git log
```
To create version/commit all changes by git
```
git commit -m "message"
```
To send version/changes to github
```
git push origin main
```
To check remote url
```
git remote -v
```
To setup CI/CD pipeline in Heroku we need-
1. HEROKU_EMAIL = syeedaf9@gmail.com
2. HEROKU_API_KEY = 88ebdc3a-9b61-4eb8-aa7e-ead3f074c79d
3. HEROKU_APP_NAME = ml-regression

BUILD DOCKER IMAGE
```
docker build -t <image name> : <tag name> .
```

> Note: Image name for docker must be in lowercase

To list docker image
```
docker images
```

Run docker image
```
docker run -p 5000:5000 -e PORT=5000 ad85da736d90
```

To check running containers in docker
```
docker ps
```

To stop docker container
```
docker stop <container_id>
```


