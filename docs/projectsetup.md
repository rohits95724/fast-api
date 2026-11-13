# to create the project.toml file use
uv init --bare


# to create the uv.lock file use 
uv lock
uv add "fastapi[standard]"


# docker build  command
docker build -t fastapi-app .

# docker run command
docker run -d -p 8000:8000 fastapi-app

# for creating the eslint type setup in python use the following command
 1) first navigate to pre-commit website and copy the code snippet for python from the website
    pip install pre-commit

 2)  pre-commit next but before that create a .pre-commit-config.yaml file in the root directory of your project and paste the code snippet you copied from the pre-commit website into that file.