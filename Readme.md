create env:
pip install pipenv

pipenv install

activate environment:
pipenv shell

Create Requirement File:
install the requirements:
pip install -r requirements.txt

download the data from:

https://www.kaggle.com/jmcaro/wheat-seedsuci

git init

dvc init
 
dvc add data_given/seeds.csv

git add .

git commit -m "first commit"

oneliner updates for readme

git add . && git commit -m "update Readme.md"

git remote add origin https://github.com/Hamshita/wheat_seeds.git

git branch -M main

git push origin main


tox command:

tox
for rebuilding:

tox -r 
pytest command

pytest -v
setup commands -

pip install -e . 
build your own package commands-

python setup.py sdist bdist_wheel

