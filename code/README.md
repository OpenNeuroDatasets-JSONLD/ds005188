For installation, we recommend the Anaconda distribution. find the installation
guide here: https://docs.anaconda.com/anaconda/install/

After you have a working version of Python 3, simply install new virtual environment via this command:

`conda create --name=mne1.6 --channel=conda-forge python=3.10 mne=1.6 numpy=1.23.1 spyder pyvista pyvistaqt pyyaml pingouin rpy2 mne-bids pyyaml numpy openpyxl autoreject`

Or use the requirements.txt file, located in this directory. For that, you can run the following command:
`conda create --name mne1.6 --file requirements.txt`
