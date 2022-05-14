# Jupyter Template

## Python Env Setup

#### 1- Create Environment
    $ python3 -m venv venv/

#### 2- Activating Environment
    # Linux / MacOS
    $ source venv/bin/activate
    
    # Windows (Command Prompt)
    $ venv\Scripts\activate

    # Windows (Git Bash)
    $ source venv/Scripts/activate

#### 3- Installing Dependencies
    # Linux / MacOS
    $ pip install -r requirements-mac.txt
    
    # Windows
    $ pip install -r requirements-win.txt

#### 4- Starting Jupyter Lab
    # Linux / MacOS
    $ venv/bin/jupyter-lab --port=8888

    # Windows (Command Prompt)
    $ venv\Scripts\jupyter-lab

    # Windows (Git Bash)
    $ venv/Scripts/jupyter-lab

#### Info: Installing Package
    $ pip install <package>
    $ pip freeze > requirements-mac.txt
    $ pip freeze > requirements-win.txt
