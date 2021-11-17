
Analysing Urban form using big data: A primer for urban data science in python
=============================
This repository contains the resources used by Christina Last for a talk in collaboration
with Kyiv University, Fulbright Ukraine and the Center for Urban Studies during October 2021.

Setup
======================
Library installation
-----
To install the dependencies required for this project we use ``poetry`` https://python-poetry.org/.
For installation enter the project directory and run::
    poetry install

Which will install the libraries locally. To create a ``virtual environment`` within which
you can execute your code run::
    poetry shell

This will spawn a shell in which you can interact with the libraries.

Kernel creation
-----
To install a kernel in order to run the notebook run the following command::

    ipython kernel install --name "local-venv" --user

To run the ``jupyter`` server enter the command::

    jupyter notebook

This will open a ``jupyter`` server in your browser's localhost. Navigate to your list of kernels and select "``local-venv``".
You will now be able to execute the cells in your ``jupyter notebook``.



