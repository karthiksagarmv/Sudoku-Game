# Sudoku-Game
Sudoku is a logic number puzzle tickling one to come up with suitable number for grid. The project aims to build a sample sudoku game using Python 


# Setup ( MacOS )
1) Install Python
2) Install Git
3) Install Pip
    > sudo easy_install pip
4) Configure Virtualenv
    If you have a project in a directory called my-project you can set up virtualenv for that project by running:

    $ cd my-project/
    $ virtualenv venv
    If you want your virtualenv to also inherit globally installed packages run:

    $ virtualenv venv --system-site-packages
    These commands create a venv/ directory in your project where all dependencies are installed. You need to activate it first though (in every terminal instance where you are working on your project):

    $ source venv/bin/activate
    You should see a (venv) appear at the beginning of your terminal prompt indicating that you are working inside the virtualenv. Now when you install something like this:

    $ pip install <package>
    It will get installed in the venv/ folder, and not conflict with other projects.

    To leave the virtual environment run:

    $ deactivate
