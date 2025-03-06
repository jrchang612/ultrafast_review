# ultrafast_review
Github Repo associated with the paper "Biophysical limits of ultrafast cellular motility" on bioRxiv. The code generates the figures used in the paper "Biophysical limits of ultrafast cellular motility" using the data stored in the excel sheet "Chang_and_Prakash_2024.xlsx".

# System requirements:
The current code base is only tested on Mac OS, Apple M3 Max Chip, with Python 3.12.4. See "requirements.txt" for the required packages. No non-standard hardware required. As the code simply generates the figures used in the paper "Biophysical limits of ultrafast cellular motility" using the data stored in the excel sheet "Chang_and_Prakash_2024.xlsx", it only requires very basic Python packages such as numpy, scipy, pandas, matplotlib, and seaborn. We expect the code to work for different Python versions and/or software package versions.

# Installation guide:
Follow the instruction of venv (https://docs.python.org/3/library/venv.html) to create a virtual environment and install the required packages as listed in "requirements.txt". We expect the typical install time to be less than 1 hour, usually limited by the time required to install the scipy package.

# Demo:
Run "ultrafast_review_plot_finalized.ipynb". The expected output is stored alongside with the jupyter notebook file. Expected run time for each figure is less than 1 minute on a typical desktop computer.

# Instruction of use:
Follow the documentation in Jupyter notebook/Jupyter Lab (https://jupyter.org/) if you are not familiar with them. You can reproduce all the results by run through the entire "ultrafast_review_plot_finalized.ipynb".

# Shared data:
see "Chang_and_Prakash_2024.xlsx".
