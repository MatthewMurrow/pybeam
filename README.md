# Welcome to PyBEAM!
PyBEAM (Bayesian Evidence Accumulation Models) is a Python package designed to rapidly fit two-threshold, binary choice models to choice-RT data using Bayesian inference methods. For a full description of its design, see the publication (https://psyarxiv.com/ax36b/). To learn how to use PyBEAM, see the "Tutorials" directory for step-by-step introductions.

# Installation

To install PyBEAM, you must first install PyMC. To do so, follow the instructions located on PyMC's website. The url for this is (as ofDecember 15, 2022):

  https://www.pymc.io/projects/docs/en/latest/installation.html

Once you have installed PyMC, you must next install the Python package Cython and a C compiliter. PyBEAM utilizes Cython to improve program speed, requiring files to be compilied. Cython is installed via pip like other Python packages. Instructions for doing this are at the following link:

    https://cython.readthedocs.io/en/stable/src/quickstart/install.html

After Cython is installed, download a compilier. For Mac, this is part of Xtools, which can be downloaded from console or the app store. If it is not already on your Mac, you will be prompted automatically to install it when you install PyBEAM. For Windows, a compilier must be downloaded separately. A couple options are available to do this. The first is to download Window's Visual Studio program. Instructions for this are at the following url (as of December 15, 2022):

    https://github.com/cython/cython/wiki/CythonExtensionsOnWindows
    
The second option is to install MinGW (NOT MinGW-64). Instructions for this are located on Cython's docs, located at this URL (as of December 15, 2022):

    https://cython.readthedocs.io/en/latest/src/tutorial/appendix.html?highlight=compile%20windows
    
We can now install PyBEAM. First, download and unzip pybeam.zip. Then, open one of conosle, command prompt, or anacond prompt (depending on your system), and navigate to the pybeam directory. In this directory there should be two files: the folder pybeam, and a setup.py file. Once there, run the following line of code (INCLUDING the period):

    pip install .
    
Once you have done this, PyBEAM is ready to be used!

# Learning to use PyBEAM

PyBEAM contains two sub-modules: pre-coded and custom. The pre-coded sub-module provides many pre-coded models from the literature which should be sufficient for most needs. The second sub-module, custom, provides tools for users to create their own models outside the scope of the pre-coded set. Tutorials for using the models are provided in Jupyter notebooks located in the folder "Tutorials".

# Custom models

Folder "custom_model_template.zip" contains the custom model template files. See "Custom_Tutorial1_creating_a_custom_model" for directions on how to use these files to create your own custom model.
