# MachineLearning_Project
This is my first ML Project

## Start Machine Learning project.

### Software and account Requirement.

1. [Github Account](https://github.com)
2. [Heroku Account](https://dashboard.heroku.com/login)
3. [VS Code IDE](https://code.visualstudio.com/download)
4. [GIT cli](https://git-scm.com/downloads)
5. [Git Documentation](https://git-scm.com/docs/gittutorial)


Creating Conda Environment
...

conda create -p venv python==3.7 -y
...

conda activate venv/
...

OR

conda activate venv
...

pip install -r requirements.txt
...


To add files to git
...
git add .
...

OR
...
git add <file_name>
...

> Note: To ignore file or folder from git we can write name of the file/folder in .gitignore file

To check the status
...
git status
...

To check all version manintained by git
...
git log
...

To create version/commit all changes by git
...
git commit -m "message"
...

To send changes/version to github
...
git push origin main
...

To check main url
...
git remote -v
...

To setup CI/CD pipeline in heroku we need 3 information

1. Heroku Email = dinesh.tncbca@gmail.com
2. Heroku API = fe8b1aec-33f1-4aa9-a7aa-012722b2ca4a
3. Heroku_App_name = ml-first-project-helloword


BUILD DOCER IMAGE:
...
docker build -t <image_name>:<tagname>

> Note: Image name for docker must be lowercase

To list docker image
...
docker images
...

Run docker image
...
docker run -p 5000:5000 -e PORT=5000 0478899b3aea
...

To check running containers in docker
...
docker ps
...

To stop docker container
...
docker stop <container_id>
...








