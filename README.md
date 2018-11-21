# Parallel Programming in Python: Multithreading and Multiprocessing

Material for the threading and multiprocessing in python workshop (Fall of 2018).

## Objectives
Learning Outcomes for attendees of this workshop:

* Able to understand the differences between multithreading and multiprocessing.
* Know which tasks are better suited for multithreading or multiprocessing
* Able to use threading and multiprocessing packages for appropriately suited tasks.

## Outline
* Overview:
  * [Jupyter Lab IDE & Notebook Basics](notebooks/jupyter_intro.ipynb)
  * [Overview of parallel computing with python](notebooks/overview.ipynb)
* [Threading:](notebooks/threading.ipynb)
  * c-extension thread enabled libraries (numpy & scipy)
  * threading package
* [Multiprocessing:](notebooks/multiproc.ipynb)
  * Process class
  * Pool class
* Other parallel libraries:
  * [pymp -- OpenMP-like functionality for Python](notebooks/pymp.ipynb)

## Running the Notebooks for this Workshop
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/git/https%3A%2F%2Fgit.rcc.uchicago.edu%2Fjhskone%2Fmultiproc_py.git/38f9bb6ce3602b73a8ddd1dbcad3f5f9a8d21f6a?urlpath=lab/tree/master.ipynb)


We will rely on cloud compute resources that you will connect to through your web browser.
In order to access an interactive environment to view and execute the jupyter notebooks,
you will need to click the *binder* link at the topleft of this section. 
This will open up a new browser window tab that will provision a lightweight docker container
on a remote cloud resource that will spin up a jupyter notebook server for you to interactively 
work with the notebooks and other content of this repo. Please have patience as the
process of cloning the repo, creating a docker image, installing all python requirements, 
and launching jupyter lab, can take a minute or more to complete. 

In the event there are technical difficulties with using mybinder, we can use
[Google's Colaboratory](https://colab.research.google.com) as a fall back. The 
Colaboratory environment is a slight modification of the jupyter notebook server, 
but essentially does the same thing. If we need to resort to using Colaboratory,
we will have to import this repository and unfortunately Colaboratory only 
supports GitHub at this time, so we will have to use a mirror of this repo in GitHub. 


