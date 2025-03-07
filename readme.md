% CSSE 461 Lecture Notebooks
% Spring 2025

## Overview

This repository hosts the notebooks and in-class codebase for the lectures in CSSE 461. I recommend 
creating a virtual Python environment for this course so that we can match package versions.

I find managing my Python environment simpler in Linux, so my workflow is based in WSL. You're 
welcome to set up a Windows-based Python environment if you prefer. Our course's officially 
supported environment is Python in Jupyter Lab, running the packages listed in `requirements.txt`.

## Setup

1. Clone the repository.

2. Create and activate a virtualenv:

   ```
   $ python3 -m venv 461env
   $ source 461env/bin/activate
   ```

3. Install the required python packages:

   ```
   $ pip install -r requirements.txt
   ```

4. Launch jupyterlab:

   ```
   jupyter lab
   ```

   and use the Jupyterlab interface to navigate around among notebooks and code files.
