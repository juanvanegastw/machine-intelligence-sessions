# Basic Tools for Machine Intelligence
## Virtual Env

Install homebrew  
`/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"`

Install python3   
`brew install python3` # This install also pip

Install virtual env  
`pip3 install virtualenv`

Command with basic packages:  
`virtualenv -p python venv`

Activate env  
`source venv/bin/activate`

Install dependencies
`pip install <package-name>`

Requirements:
* pip install numpy
* pip install matplotlib
* pip install scipy
* pip install tqdm
* pip install scikit-learn
* pip install jupyter

Create requirements.txt file  
`pip freeze > requirements.txt`

[Our requirements](requirements.txt)

Install with requirements
`pip install -r requirements.txt`  

## Jupyter Notebooks

Open jupyter notebook
* Verify that you have your environment activated `source venv/pip/activate`  
* Run `$ jupyter notebook`

Resources
* [Jupyter Notebook](Jupyter_Notebook_CheatSheet_Edureka.pdf) from <sub><sup>https://www.edureka.co/blog/wp-content/uploads/2018/10/Jupyter_Notebook_CheatSheet_Edureka.pdf</sup></sub>

