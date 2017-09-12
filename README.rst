Hopsworks API Docs
==================

This repository contains sources for the documentation of the Hopsworks REST API.

Dependencies
------------

Building these docs requires having python2.7 and virtualenv installed.

::

  sudo apt install python2.7 virtualenv

If you want to compile the documents to pdf, you will also need texlive.

::
  
  sudo apt install texlive texlive-latex-extras latexmk

Building the documentation
--------------------------

Clone this project

:: 

  $ git clone https://github.com/hopshadoop/hopsworks-api-docs
  $ cd hopsworks-api-docs
  
Create and enter a virtualenv

::
   
   $ virtualenv --python=python2.7 venv
   $ source venv/bin/activate

Install dependencies

::

   (venv)$ pip install -r requirements.txt

Build the docs

::

   (venv)$ cd docs
   (venv)$ make htlm // output: _build/html
   (venv)$ make pdflatex // output: _build/latex
   
Exit the virtualenv

::

  (venv)$ deactivate

Contribute
----------

- Issue Tracker: https://github.com/hopshadoop/hopsworks-api-docs/issues
- Source Code: https://github.com/hopshadoop/hopsworks-api-docs

Support
-------

If you are having issues, please let us know.
We have a mailing list located at: hopshadoop@google-groups.com

License
-------

The project is licensed under the Apache v2 license.
