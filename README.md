## Boston House Pricing Prediction

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
conda activate C:\Users\admi\Desktop\ineuron\Knaik_sir\Boston_proj\bostonhousepricing\venv
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
install preexisted venv
```
conda install -p c:\Users\admi\Desktop\ineuron\Knaik_sir\Boston_proj\bostonhousepricing\venv ipykernel --update-deps --force-reinstall
```