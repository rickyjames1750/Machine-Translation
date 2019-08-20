# Introduction
In this notebook, This project will build a deep neural network that functions as part of an end-to-end machine translation pipeline. The completed pipeline will accept English text as input and return the French translation.

# Setup

This project requires GPU acceleration to run efficiently. Support is available to use either of the following two methods for accessing GPU-enabled cloud computing resources.

## Google Colab or Kaggle (Recommended)

These platforms provide remote connection to GPU-enabled instances right from their platform. Refer to each sites instructions to find an overview of navigating & using Jupyter notebook with each respective site.

## Amazon Web Services (Optional)

Please refer to YouTube University(Meaning just search on YouTube) for instructions for setting up a GPU instance for this project, and refer to the project instructions in the classroom for setup. The recommended AMI should include compatible versions of all required software and libraries to complete the project.

## Install
- Python 3
- NumPy
- TensorFlow 1.x
- Keras 2.x

# Finalize
When you are ready to finalize your project, do the following steps:
1. Submit the following in a zip file to your github remote repository:
  - `helper.py`
  - `machine_translation.ipynb`
  - `machine_translation.html`

## Converting to HTML

There are several ways to generate an HTML copy of the notebook:

 - Running the last cell of the notebook will export an HTML copy

 - Navigating to **File -> Download as -> HTML (.html)** within the notebook

 - Using `nbconvert` from the command line

    $ pip install nbconvert
    $ nbconvert machine_translation.ipynb
