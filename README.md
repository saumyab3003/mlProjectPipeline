** End to End Machine Learning Project **

1) Create virtual environment
    conda create -p venv python==3.10 -y
    conda activate venv/
2) Setup Git Repository
    git init
    git add README.md
    git commit -m "first commit"
    git branch -M main
    git remote add origin https://github.com/saumyab3003/mlProjectPipeline.git

    If doing for the first time: 
    https://git-scm.com/book/en/v2/Customizing-Git-Git-Configuration

    git push -u origin main

3) Create .gitignore file in Github and set the template to Python. Finally commit the file in Git.

4) pull the repo changes by : git pull

5) Create setup.py & requirements.txt
    The setup script is the centre of all activity in building, distributing, and installing modules using the Distutils.

6) Create src to install pacakges.

7) run pip install -r requirements.txt on terminal
    this will build the package mlproject.egg-info file

8) Push everything to git
    git add .
    git commit -m "msg"
    git push

9) Create folder structure in src

10) Develop in Logger.py and exception.py
