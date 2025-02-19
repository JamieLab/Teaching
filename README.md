# Teaching

A selection of iPython Jupyter notebooks are available for teaching. The code is available (via the github directories) and through the ICOS Jupyter cloud system.

ICOS Jupyter system: https://exploredata.icos-cp.eu/hub/login <br/>
Username is: student email address (e.g: df391@exeter.ac.uk)<br/>
Password is: francis

# Local setup
The conda environment can be setup locally to run the Jupyter notebooks if the ICOS system is unavailable. Steps to follow for this: <br/>
1) Head to Github releases on the right hand side, and download the zip file of the latest release<br/>
2) Unzip this zip file in your downloads folder (for student accounts moving this to the Documents didn't seem to work)<br/>
3) Open a command prompt in windows (Click the Windows icon, search for 'command prompt')<br/>
4) Using the cd command move from the starting location to the downloads folder (likely just 'cd Downloads'). You can see the current location in the command prompt<br/>
5) Using the cd command move into the unzip Teaching folder (like requiring cd down two directories, as unzip puts the folder inside a folder)<br/>
6) Run the 'conda_setup.bat' - this deletes the Python environment, and regenerates it if required and then activates it.<br/>
7) Run the command 'jupyter notebook' - This launches the Jupyter notebook server locally, and then a browser will open with the notebook environment<br/>
8) Navigate within the Jupyter notebook system to the Notebooks folder, and then each folder contains a Jupyter notebook the same as on the ICOS system. 

# Legacy
Also available on a legacy Binder installation which generates a Binder instance (on a cloud system) so that all notebooks can be run within any web browser. Not been tested recently

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/JamieLab/Teaching/HEAD)

# Development
Developed initially by Sayooj Prabhakaran Nair and Jamie Shutler, with further updates by Daniel Ford
