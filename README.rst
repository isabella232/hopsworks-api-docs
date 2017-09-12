Hopsworks API Docs
==================

This is the documentation of the REST-api of the Hopsworks platform.

Building the documentation
--------------------------

   // Get the source

   git clone https://github.com/hopshadoop/hopsworks-api-docs
   cd hopsworks-api-docs
   
   // Create and enter a virtualenv
   virtualenv --python=python2.7 venv
   source venv/bin/activate

   //Install the dependencies
   pip install -r requirements.txt

   //Optional: if you want to compile to pdf, you'll need texlive
   sudo apt install texlive texlive-latex-extras latexmk
   
   # Build the docs
   cd docs
   make htlm //html-files will be output in the _build/html dir

   make pdflatex //pdf will be output in the _build/latex dir
   
   // Exit the virtualenv
   deactivate

Contribute
----------

- Issue Tracker: github.com/hopshadoop/$project/issues
- Source Code: github.com/hopshadoop/

Support
-------

If you are having issues, please let us know.
We have a mailing list located at: hopshadoop@google-groups.com

License
-------

The project is licensed under the Apache v2 license.
