==========
pythonbase
==========

pythonbase provides a skeleton for creating Python projects, complete with Sphinx docs, PyPI integration, etc.

Basic setup
===========

#. Copy the directory structure and files of Pythonbase to your project.
#. Make changes to all these files as necessary (e.g., by grep'ing for "pythonbase" and replacing with your project and also grep'ing for "Anubhav Jain" and replacing with your name).
#. Run ``python setup.py develop`` in your new project to install it on your system
#. Run ``python setup.py release`` to release your project to PyPI. Congratulations, your project can now be installed!

(The last step probably requires PyPI registration; fill in details once I get a good test case for a new user).

Docs setup
==========

#. Note that the docs are in the "docs" subfolder in rst format to be built by Sphinx.
#. Import the project into readthedocs.org; hopefully, the docs should be auto-detected.


CircleCI setup
==============

#. Log into CircleCI, and build your project.

The Pythonbase docs are located as `here <http://pythonbase.readthedocs.io/en/latest>`_