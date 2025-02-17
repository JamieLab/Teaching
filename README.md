# Teaching

A selection of iPython Jupyter notebooks are available for teaching. The code is available (via the github directories) and through the ICOS Jupyter cloud system.

ICOS Jupyter system: https://exploredata.icos-cp.eu/hub/login
Username is: student email address
Password is: francis

#Local setup
The conda environment can be setup locally to run the Jupyter notebooks if the ICOS system is unavailable. This requires downloading the Github repository as a zip and unzipping the repository. Open a command prompt and 'cd' to the folder with the repository. Run conda_setup.bat, which generates the environment in conda (tested on UoE computers) - if the environment has already been generated, then use 'conda activate JamieLab_Teaching' to activate the environment. Once complete the conda environment is activated, and the command 'jupyter notebook' can be run, which starts the Jupyter notebook server, then a internet browser will start with the Jupyter notebooks.

#Legacy
Also available on a legacy Binder installation which generates a Binder instance (on a cloud system) so that all notebooks can be run within any web browser. Not been tested recently

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/JamieLab/Teaching/HEAD)

#Development
Developed initially by Sayooj Prabhakaran Nair and Jamie Shutler, with further updates by Daniel Ford
