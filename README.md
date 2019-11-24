Readme
======

 The purpose of this program is to offer good programming practices in 
 Python, when you want to build a program that can go to a production
 target.
 
 You can then look at how to structure a project and its various
 components. And inspire you to create a new project or improve the 
 quality of existing projects.

 The different topics that are covered in this model are:
  - how to structure a project to deploy it in a production environment,
  - that must contain a file requirement_dev.txt,
  - that must contain files setup.cfg and setup.py,
  - how to individually test components of a project with pytest,
  - how to create logs that are visible on the console and also written
    in log files,
  - how to configure the logs with an external yaml file,
  - how to manage the exeptions of execution of a program,
  - how to document your code to make it more understandable and use
    Sphinx to create the documentation of your project,
  - how to structure your project to publish it in the form of a
    bookstore,
  - how to document the project with sample files: readme.md, authors.md,
    contributing.md, installation.md, usage.md, ...
 
UniqueWordList
--------------
 Extract from a file in RTF format a list of all the words in the file 
 without repetition.
 
 The object of this program is to read a text and extract the list of 
 words without repetition. The functional interest is thus voluntarily 
 limited, to allow a developer who wishes to take note of some good 
 programming practices, to study them and to draw inspiration from them,
 without being too disturbed by the understanding of what the main 
 program and its modules does.

 This project was structured with Cookiecutter_ to have a good example 
 of a project in Python. You will find examples: tests components,
 modules structuring, documentation in the project components to 
 then create the documentation with Sphinx and a mechanism for 
 log management to the console and log files. Finally, this project 
 can be packaged with Setuptools.

* Free software: GNU General Public License v3


Features
--------

* TODO

Credits
-------

This package was created with Cookiecutter_ and the `audreyr/cookiecutter-pypackage`_ project template.

.. _Cookiecutter: https://github.com/audreyr/cookiecutter
.. _`audreyr/cookiecutter-pypackage`: https://github.com/audreyr/cookiecutter-pypackage
