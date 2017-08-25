Data Analysis with Python
=========================

Companion code for my video course on [Data Analysis with Python](https://www.packtpub.com/application-development/data-analysis-python-video), published by Packt Publishing.

Videos on [PacktPub's Mapt](https://www.packtpub.com/application-development/data-analysis-python-video) (the publisher)

Videos on [OReilly's Safari Online](https://www.safaribooksonline.com/library/view/data-analysis-with/9781788290548/)

Setting up the environment
-----

Requirement: Python `3.6`

The suggestion is to use the [Anaconda distribution](https://continuum.io/downloads "Download Anaconda Python").

Create and activate a `conda` environment:

    conda create --name packt-py36 python=3.6 --yes
    source activate packt-py36  # Linux / macOS
    activate packt-py36  # Windows

Install the libraries used in the course:

    conda install --file conda-reqs.txt --yes

Launch Jupyter notebook:

    jupyter notebook
