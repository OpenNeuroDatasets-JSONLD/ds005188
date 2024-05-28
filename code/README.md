1. For installation, we recommend the Anaconda distribution. Find the installation guide here: [Anaconda Installation Guide](https://docs.anaconda.com/anaconda/install/).

2. After you have a working version of Python 3, simply install a new virtual environment via this command in the Ubuntu terminal or Anaconda Prompt for Windows OS:

`conda create --name=mne1.4 --channel=conda-forge python=3.10 mne=1.4.1 numpy=1.23.1 spyder pyvista pyvistaqt pyyaml pingouin rpy2 mne-bids pyyaml numpy openpyxl autoreject`


Or use the requirements_xxxxxx.txt files located in this directory:
- For Ubuntu OS (version 20 and above), please use requirements_for_ubuntu_2x.txt.
- For Windows OS (version 10 and above), please use requirements_for_windows_1x.txt.

To do this, you can run the following command in the Ubuntu terminal or Anaconda Prompt for Windows OS:
`conda create --name mne1.4 --file <requirements_filename>`

3. Activate the created environment:
`conda activate mne1.4`

4. Start your favorite IDE with this environment. For example, to start Spyder IDE, use this command after activating the environment:
`spyder`

5. To start processing data, go to the directory with the downloaded data and open the Python scripts of interest. (If you are using Spyder IDE, use the "Files" pane located in the upper right corner of the workspace.)