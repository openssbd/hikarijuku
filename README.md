# Hikarijuku 2019
Tutorial for Hikarijuku 2019

Hikarijuku (光塾) is the community group for bio-imaging especially for young scientists in Japan. Hikari means light in Japanese and juku means lesson/tutorials. It was originally formed in 2004. For more details http://hikarijyuku.mad.buttobi.net/ (in Japanese only).

The code in this directory was used as a tutorial for the meetup on Nov 12-13 2019 in Kobe.
It tried to demonstrate the use of accessing SSBD using Python and Jupyter notebook through Google's Colab.
The code has not been thoroughly checked and may not be scientifically valid. It was used as a tutorial for accessing the online public database.

To run the notebooks, you can either [run on mybinder.org](https://mybinder.org/v2/gh/openssbd/hikarijuku/master?filepath=ImageSeries.ipynb) or build locally with [repo2docker](https://repo2docker.readthedocs.io/)

To build locally:

 * Install [Docker](https://www.docker.com/) if required
 * Create a virtual environment and install repo2docker from PyPI.
 * Clone this repository
 * Run  ``repo2docker``. 
 * Depending on the permissions, you might have to run the command as an admin


```
pip install jupyter-repo2docker
git clone https://github.com/openssbd/hikarijuku.git
cd hikarijuku
repo2docker .
```