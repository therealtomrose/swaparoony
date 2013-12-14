swaparoony
==========

An automated bitcoin arbitrage platform


Requirements
============


python
------

Make sure you are running python 2.7: http://www.python.org/download

git
---

Make sure you have git http://git-scm.com/


Clone git repo
==============


- Make a directory where you will store hangout (suggestions below)::

    mkdir ~/projects
    mkdir ~/projects/swaparooni
    cd ~/projects
    git clone https://github.com/therealtomrose/swaparoony.git swaparoony


Setup Virtual Env
=================


Create virtual environment
--------------------------

Do this where the project will live e.g. 'hangout'
- install virtualenv::

    sudo easy_install pip
    sudo pip install virtualenv

- install a new virtual environment in the directory where the project will live::

    cd ~/projects
    virtualenv --no-site-packages swaparooni
    sudo pip install -U versiontools

- configure the local python path::

    echo 'export PYTHONPATH=$PYTHONPATH:~/projects/swaparooni' >> ~/projects/swaparooni/bin/activate
    echo 'export PATH=~/projects/swaparooni:$PATH' >> ~/projects/swaparooni/bin/activate


Install requirements
--------------------

- Run the pip installer with a requirements file.::

    cd ~/projects/swaparooni
    source bin/activate
    sudo pip install -r requirements.txt


Configure Settings
==================

- Make a copy of the settings template file and enter your local settings:

    cd ~/projects/swaparooni
    cp settings_local.template settings_local.py


Running
=======


Load Virtual Environment
------------------------

::

    cd ~/projects/swaparooni
    source bin/activate


Run Swaparooni
-----------

::

    TBD
