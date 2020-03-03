## Machine Learning:

### Word of introduction
This course is composed of 6 lectures and number of practical tasks in Python.

The content is heavily based on materials by [Toby Breckon](http://breckon.eu/toby/teaching/mltutorial/) and [Andrew Ng](https://www.coursera.org/learn/machine-learning/).

Sessions:
1. Basic Predictive Models
2. Image Features
3. Unsupervised Learning
4. Supervised Learning
5. Deep Learning

This course uses *Jupyter Lab*, an in-browser code editing environment for Python, R, Julia and many more languages. The easiest way to install it, as well as all required libraries is using Anacoda - a Python framework.

Prepared and presented for the first time by [Mikolaj (Miks) Kundegorski](https://mixmixmix.github.io) with help from [Chas Nelson](https://chasnelson.co.uk) for Python For Bioimage Analysis Course in Cambridge, December 2019. 
The second session took place in March 2020 at CES, IISC, Banaglore, India.

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
3. Run `conda env create -f learnmachine_env.yml`. This installs all the prerequisite packages for the course in a virtual environment called 'learnmachine_env'.
4. Run `conda activate learnmachine_env`. This moves you into the virtual environment.
5. Run `python -m ipykernel install --user --name=learnmachine_env`. This makes this virtual environment available as a kernel in Jupyter lab.
6. Run `conda deactivate` to leave the virtual environment.
7. Start Jupyter Lab, either through Anaconda Navigator or by running `jupyter lab` in a terminal.

You will need to change the kernel for each notebook from the default 'Python 3' notebook to the 'learnmachine_env' notebook. You can do this by clicking where it says 'Python 3' in the top right or bottom left of a Jupyter Lab window.

### To learn how to use course:

Our Python for Beginners course provides all information needed to use Jupyter Lab and key Python libraries: https://github.com/ChasNelson1990/python-zero-to-hero-beginners-course

### Running Tasks

There are four tasks corresponding to the Sessions 1, 3 and 4. To perform those download `simple_blobs.zip` from [here](https://www.dropbox.com/sh/0s1mo71j99p1di3/AACscxEOM1mXnGhIZICCoMMDa?dl=0) and unzip in `tasks/assets` directory.



### Running CNN example

`demo_cnn.ipynb` is a demonstration of CNN in Keras solving the problem of blob classification.

You need some additional reep learning libraries to run this example. Use another virutal environment for this occasion:

```
conda env create -f deeplearn_env.yml
conda activate deeplearn_env
python -m ipykernel install --user --name=deeplearn_env
conda deactivate
```
Then, restart the jupyter lab and choose `deeplearn_env` kernel.
