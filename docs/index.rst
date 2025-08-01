
.. roman_shear_sims documentation main file.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

roman-shear-sims
================

The package `roman-shear-sims` is meant to help for the development of shape
measurement methods. This package intends to provide a way to create fast simulations
of single exposures images for the Roman Space Telescope.


.. toctree::
   :maxdepth: 5
   :caption: API

   autoapi/index


Dev Guide - Getting Started
---------------------------

Before installing any dependencies or writing code, it's a great idea to create a
virtual environment. LINCC-Frameworks engineers primarily use `conda` to manage virtual
environments. If you have conda installed locally, you can run the following to
create and activate a new environment.

.. code-block:: console

   >> conda create env -n <env_name> python=3.11
   >> conda activate <env_name>


Once you have created a new environment, you can install this project for local
development using the following commands:

.. code-block:: console

   >> pip install -e .'[dev]'
   >> pre-commit install
   >> conda install pandoc


Notes:

1) The single quotes around ``'[dev]'`` may not be required for your operating system.
2) ``pre-commit install`` will initialize pre-commit for this local repository, so
   that a set of tests will be run prior to completing a local commit. For more
   information, see the Python Project Template documentation on
   `pre-commit <https://lincc-ppt.readthedocs.io/en/latest/practices/precommit.html>`_.
3) Installing ``pandoc`` allows you to verify that automatic rendering of Jupyter notebooks
   into documentation for ReadTheDocs works as expected. For more information, see
   the Python Project Template documentation on
   `Sphinx and Python Notebooks <https://lincc-ppt.readthedocs.io/en/latest/practices/sphinx.html#python-notebooks>`_.


.. toctree::
   :hidden:

   Home page <self>
   API Reference <autoapi/index>
   
