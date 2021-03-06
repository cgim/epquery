.. _Installation:

============
Installation
============

Curently the only way to install **EPQuery** is by cloning its repository and installing using pip
from the local directory::

    git clone https://github.com/sdu-cfei/epquery.git epquery
    cd epquery
    pip install .

On Ubuntu 16.04 and later, if you run into a permission error, you might want to install in the user directory::

    pip install --user .

If you plan to modify the source code, it is advised to install in the editable mode::

    pip install --user -e .

**EPQuery** depends only on **numpy** and **fuzzywuzzy** packages, which should be installed automatically by pip if needed.
In case of problems, you can install them separately::

    pip install numpy
    pip install fuzzywuzzy[speedup]

To uninstall::

    pip uninstall epquery
