# Greeknames Project Skeleton

This skeleton is the start of a real project.
Replace the code at will. But check out the illustrated
facilities; this is a running, and unit testable project:

Features that are demonstrated are:

    o Class/method setup
    o Unit testing in an object-oriented context
    o Argparse
    o Creation of executable script using #!
    o Use of setup.py

Analysis of ancient Greek names

Experimental classifier that syllabifies ancient Greek names,
and predicts the associated person's status or profession.

Tne method discovers association rules of syllables in names
recovered during excavations. The sparsity of available data allows
for exhaustive methods.

# Installation

    o git clone git@github.com:paepcke/greeknames.git
    o cd greeknames
    o Optionally create an anaconda environment (highly recommended)
         conda new -s greeknames
    o python setup.py install

# To run:

    o Make sure you are in .../greeknames
    o Show off the commanline nicety created via argparse:
          src/greek_name_classifier.py -h
    o Run the unit tests:
          nose2
    o Run the program with a tiny name file:
          src/greek_name_classifier.py src/tests/data/tst_names.txt
    
