# Data analysis
- Document here the project: snake_conservation_status
- Description: I'd like to compare the distribution and IUCN status of terrestrial snake species with recent drought episodes
- Data Source: World's most endangered snakes on Kaggle (https://www.kaggle.com/datasets/kkhandekar/conservation-status-of-the-worlds-snakes), distribution data from IUCN
- Type of analysis: visualisation, correlation analysis

Please document the project the better you can.

# Startup the project

The initial setup.

Create virtualenv and install the project:
```bash
sudo apt-get install virtualenv python-pip python-dev
deactivate; virtualenv ~/venv ; source ~/venv/bin/activate ;\
    pip install pip -U; pip install -r requirements.txt
```

Unittest test:
```bash
make clean install test
```

Check for snake_conservation_status in github.com/{group}. If your project is not set please add it:

Create a new project on github.com/{group}/snake_conservation_status
Then populate it:

```bash
##   e.g. if group is "{group}" and project_name is "snake_conservation_status"
git remote add origin git@github.com:{group}/snake_conservation_status.git
git push -u origin master
git push -u origin --tags
```

Functionnal test with a script:

```bash
cd
mkdir tmp
cd tmp
snake_conservation_status-run
```

# Install

Go to `https://github.com/{group}/snake_conservation_status` to see the project, manage issues,
setup you ssh public key, ...

Create a python3 virtualenv and activate it:

```bash
sudo apt-get install virtualenv python-pip python-dev
deactivate; virtualenv -ppython3 ~/venv ; source ~/venv/bin/activate
```

Clone the project and install it:

```bash
git clone git@github.com:{group}/snake_conservation_status.git
cd snake_conservation_status
pip install -r requirements.txt
make clean install test                # install and test
```
Functionnal test with a script:

```bash
cd
mkdir tmp
cd tmp
snake_conservation_status-run
```
