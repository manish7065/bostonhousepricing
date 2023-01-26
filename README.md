## Boston House Pricing Prediction with deployment

This is just a demo project to learn the pickling, dockerization and deployment process.
The dataset has taken from sklearn library of python.

### Software & Tools Requirements

1. [Github Account](https://github.com)
2. [VS Code IDE](https://code.visualstudio.com/)
3. [Heroku Account](http://heroku.com)
4. [Git CLI](https://git-scm.com/book/en/v2/Getting-Started-The-Command-Line)

## Create a new environment

To create a new environment
```
conda create -p venv python==3.7 -y
```
To refresh the env if getting some installation error
```
conda update -n base -c defaults conda 
```
To activate the new envirenment
```
conda activate venv
```
Give the full path if above command dosent work
```
conda activate C:\Users\admi\Desktop\bostonhousepricing\venv
```
Install all the dependencies
```
pip install requirements.txt
```
To check the user of git
```
git config --global user.name
```
To check email of git
```
git config --global user.email
```
Steps to run it in [docker playgroung](https://labs.play-with-docker.com/)

Step:1 Clone the repository
```
git clone https://github.com/manish7065/bostonhousepricing.git
```
Step:2 Chande the directory
```
cd bostonhousepricing
```
Step:3 Build the docker
```
docker build -t demo:latest
```
Step:4 Runthe docker on port 8080 you can get the inmage ID by using 'docker images' command
```
docker run -p 8080:8000 -e PORT=8000 <Image ID>
