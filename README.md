# EEG
Repo containing python code for EEG data processing and analysis.

In order to open the notebooks, you'll need to have a python environment installed on your computer. I do recommend using Anaconda for this.

You can download and install Anaconda for Windows from here: 
- https://docs.anaconda.com/anaconda/install/windows/ 

Watch this video for setup details: 
- https://www.youtube.com/watch?v=WUeBzT43JyY 

Once you have Anaconda set, you can configure your python environment.

Either create a new environment and install your packages inside it, or use the default environment that Anaconda has created for you. I recommend the first option.

- To create a new custom conda environment, open the Anaconda Prompt from Start Menu and run: 
  - conda create --channel=conda-forge -n eeg python=3.10 numpy pandas plotly matplotlib==3.7.1 scipy ipykernel nbformat xlrd openpyxl mne-base

- To remove an environment use the same approach as above and run: 
  - conda remove --name eeg --all

Open up Anaconda Navigator from your start menu and start Jupyter Notebook.
This will open up Jupyter in your web browser or you may get a popup asking you how to open the HTML file - choose your default browser.

When Jupyter opens, you will see a list of folders. Choose a folder of your liking (Documents for instance) and create a new folder there to paste the notebook and the "data" folder from the repo.

Navigate to your new folder and open the notebook, and make sure you have the data directory in the folder where the jupyter notebook is.

Alternatively, download and install VSCode - https://code.visualstudio.com/download

Properly setting up VSCode with Anaconda requires the configuration of an environment variables. To set them up on a windows machine, add these paths to Path:
- Start Menu -> Environment Variables -> Edit the Path under User Variables.
  - C:\ProgramData\Anaconda3\Scripts\conda.exe
  - C:\ProgramData\Anaconda3
  - C:\ProgramData\Anaconda3\Bin
  - C:\ProgramData\Anaconda3\Scripts
