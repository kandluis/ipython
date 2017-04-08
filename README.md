# iPython Notebooks
A collection of iPython Scripts for exploring data.

# Installation
We recommend that you have virtualenv set-up in order to keep your environment clean.

Then simply run:

'''
workon <VIRTUALENV>
pip install -r requirements.txt
python -m ipykernel install --user --name=<VIRTUALENV>
'''

The launch the Jupyter Notebook:

'''
jupyer notebook
'''

and Go To Kernel->Change Kernel-><VIRTUALENV>


## Scripts
A brief summary of the included scripts.

### Generate Large Graphs Quickly
A simple python script using numpy to generate large random graphs rapidly.

### Good Reads
A simple notebook for impersonating a user in GoodReads and finding the intersection of shelved books through we scraping.

### Settlers of Catan
A solver for the Settlers of Cata Game based on optimizing future expected return.

### WikiData 
A Collaborative Filtering Model for Predicting user plays of an artist.
