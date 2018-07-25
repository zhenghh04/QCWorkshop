# Quantum Computing with ProjectQ. 

## Install Python packages

### Installing Anaconda
#### For Linux
#wget https://repo.anaconda.com/archive/Anaconda3-5.2.0-Linux-x86_64.sh
#sh ./Anaconda3-5.2.0-Linux-x86_64.sh
#### For MacOS
wget https://repo.anaconda.com/archive/Anaconda3-5.2.0-MacOSX-x86_64.pkg
sudo installer -pkg Anaconda3-5.2.0-MacOSX-x86_64.pkg -target /

### Installing ProjectQ
pip install projectq

### Installing QuTip
pip install qutip

## Test whether your installation is successful
#Please try to execute the jupyter notebook. Type jupyter-notebook in your terminal, this will lead you to the browser, and then navigate to the notebooks in the folders IntroQM and Deutsch, click the ‘*.ipynb’ file. This should open another browser window. Execute the first cell, which should have ‘import’ statements. If ‘nothing’ happens (i.e., there is no error message), everything should work!
