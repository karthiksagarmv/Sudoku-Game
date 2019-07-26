# Sudoku-Game
Sudoku is a logic number puzzle tickling one to come up with suitable number for grid. The project aims to build a sample sudoku game using Python. I absolutely love playing number games so why not build the game instead of just playing it !!


# Setup ( MacOS )
1) Install Python
2) Install Git
3) Install Pip
    ```
    sudo easy_install pip
    ```
4) Configure Virtualenv
    If you have a sample-project, run below commands to setup new virtual environment venv:
    ```
    cd sample-project/
    virtualenv venv
    ```
    If you want your virtualenv to also inherit globally installed packages run:
    ```
    virtualenv venv --system-site-packages
    ```
    These commands create a venv/ directory in the project where all dependencies are installed without conflicting any libraries outside the project directory:
    
    To Enter Venv
    ```
    source venv/bin/activate
    ```
    You should see a (venv) appear at the beginning of your terminal prompt indicating that you are working inside the virtualenv. Now when you install something like this:

    ```
    pip install <package>
    ```
    It will get installed in the venv/ folder only.
    To leave virtual environment:
    ```
    deactivate
    ```
