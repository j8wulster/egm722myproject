# egm722myproject
Set-up/installation
#Required set-up
  The initial required steps for working with this code comprise of ensuring both conda and git are installed on the user’s computer. 
  To install git, go to the download site: https://git-scm.com/downloads (remember to select the correct installer based on your computer operating system).
  Next, conda can either be installed through Anaconda Navigator via a graphical interface: https://www.anaconda.com/download/success
  Alternatively, conda can also be installed with miniforge via a command line interface: https://conda-forge.org/download/
  Link to GitHub repository: https://github.com/j8wulster/egm722myproject
#Optional set-up
  GitHub: signing up for a GitHub account is free and enables greater familiarity with git version control but is not a requirement. 
  Integrated Development Environment (IDE) Use of an IDE can be helpful when writing, editing and testing code such as PyCharm Community Edition (free) available here: https://www.jetbrains.com/pycharm/download/
  Or VSCode available here: https://visualstudio.microsoft.com/downloads/
  JupyterLabs has been used to compile ipynb files for this project: https://jupyter.org/install
Set-up of conda environment
  With Anaconda Navigator installed, the next stage is to create a conda environment within which to run the code by importing the environment.yml file located in the git repository. 
  To do this, select the Environments tab and then the Import button.
  Or the following command can be run from the directory where the cloned project repository is located: conda env create -f environment.yml
