### Word of introduction

This course uses *Jupyter Lab*, an online code editing environment for Python, R, Julia and many more languages. The easiest way to install it, as well as all required libraries is using Anacoda - a Python framework.

### To install Anaconda

* *Windows:*
  1. Download the Python 3.7 Anaconda for Windows installer from (https://www.anaconda.com/distribution/#windows).
  2. Install using the installation defaults.
* *MacOS:*
  1. Download the Python 3.7 Anaconda for macOS installer from (https://www.anaconda.com/distribution/#macos).
  2. Install using the installation defaults.
* *Linux:*
  1. Download the Python 3.7 Anaconda for Linux installer from (https://www.anaconda.com/distribution/#linux).
  2. Open a terminal window and navigate to your Downloads folder (see the Files and Directories page).
  3. Type `bash Anaconda3-` and press [Tab] twice, the full name of the file you downloaded should appear.
  4. Press [Return] and follow the text-only prompts:
    * Use [Spacebar] to scroll through the license, then type `yes` and press [Return] to approve
    * Press [Return] to approve the default location
    * Type `yes` and press [Return] to add Anaconda to your path.
    
### To install all required libraries and get the materials for this course.

To get the materials for this course clone this repository using github, or press green button "Download as ZIP"

1. Unzip the downloaded file.
2. Open a terminal and navigate to the unzipped folder, or clonned repository, e.g. `cd ./learnmachine/`.
3. Run `conda env create -f environment.yml`. This installs all the prerequisite packages for the course in a virtual environment called 'learnmachine_setup'.
4. Run `conda activate bioimage`. This moves you into the virtual environment.
5. Run `python3 -m ipykernel install --user --name=learnmachine_setup`. This makes this virtual environment available as a kernel in Jupyter lab.
6. Run `conda deactivate` to leave the virtual environment.
7. Start Jupyter Lab, either through Anaconda Navigator or by running `jupyter lab` in a terminal.

You will need to change the kernel for each notebook from the default 'Python 3' notebook to the 'learnmachine_setup' notebook. You can do this by clicking where it says 'Python 3' in the top right or bottom left of a Jupyter Lab window.

### To learn how to use course:

In Jupyter lab choose `01_running-python.ipynb` to learn how to use the notebooks.
