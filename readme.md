# Introduction

These are the solution files for the endterm exam and assignment of BDA-483 (Data Science & Computational Thinking). Questions were based on probability and statistics. We had to write out programs to verify some theoretical results while also answering some core concept questions.

I have written out my solutions in Jupyter notebooks.

Below will be given detailed instructions on the installation and compilation of the files.

# File/Folder list

- Assignment (Folder for assignment solutions)
  - Question 1.ipynb (Jupyter notebook for Q1 --Random Number Sequence) [<u>not completed]</u>
  - Question 2.ipynb (Jupyter notebook for Q2 --Stock Market Random Walk)
  - Question 3.ipynb (Jupyter notebook for Q3 --Sampling Distribution)
  - Question 4.ipynb (Jupyter notebook for Q4 --Central Limit Theorem)
- Exam (Folder for exam solutions)
  - Question 1.ipynb (Jupyter notebook for Q1 --Two-Armed Bandit Problem)
  - Question 2.ipynb (Jupyter notebook for Q2 --Page Rank Algorithm)
  - Question 3.ipynb (Jupyter notebook for Q3 --Maximum likelihood poisson distribution)
  - img (Folder for images used in jupyter notebooks)
- BDA 483 End Term Question Paper Monsoon 2020.pdf (Question paper)
- Question2.pdf (File for question 2 of question paper)
- environment.yml (file containing all packages used)

&nbsp;

## Questions in Jupyter Notebooks

The detailed explanation of code and theory is provided in the notebook itself with various plots.

&nbsp;

# Installation

I created a local environment in my machine so that the project can be managed properly. The advantages of this is that there the versions and software used in a project can be kept track of and the project can be migrated without worrying about any version issues. Before, cloning this environment the only requirement is to have Miniconda (Lite version of Anaconda) installed on your machine from here.

- https://docs.conda.io/projects/conda/en/latest/user-guide/install/

After successful installation, open the terminal/command prompt in the same directory as the project and run the following command to create a local environment from environment.yaml file to install all the dependancies and package versions used.

```console
conda env create -f environment.yaml
```

This will create a local environment and provide all the packages used namely, jupyter notebook, numpy, pandas, matplotlib etc.

To activate the environment, run:

```console
conda activate ds_midterm
```

For MacOS this may be:

```console
source activate ds_midterm
```

Now, the terminal will have the name of the environment appear at the front indicating that we are successfully in the local environment and we can run Jupyter notebooks in the same directory.
