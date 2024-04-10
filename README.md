# ML4Proteins
Welcome to ML4Proteins! Here you will learn about the concepts and methods of machine learning for protein engineering.

## Getting Started
To get started with the course material, I highly recommend setting up a Conda environment. Conda is an open-source package management and environment management system that makes it easy to install, run, and update software packages and their dependencies. You can choose between Conda and Miniforge for your setup. Conda is more comprehensive, while Miniforge is a minimal installer for Conda specifically designed for conda-forge.

## Installation Steps
Installing Conda or Miniforge:

### Conda
Visit the Anaconda distribution page and download the installer for your operating system. Follow the installation instructions provided on the website.
### Miniforge 
Visit the [Miniforge GitHub page](https://github.com/conda-forge/miniforge) and download the installer for your operating system. Follow the installation instructions provided in the repository.

### Creating a New Environment
Open your terminal (or Anaconda Prompt if you're on Windows) and create a new Conda environment specifically for this course by running:

```
conda create --name ml4proteins python=3.8
Here, ml4proteins is the name of the environment, and python=3.8 specifies the Python version.
```


### Activating the Environment
Activate the newly created environment with:

```
conda activate ml4proteins
```

## Installing Required Packages
With your environment activated, install the necessary packages for the course. These may include libraries for machine learning, data manipulation, and specific tools for protein analysis. For example:

```
conda install numpy pandas scikit-learn matplotlib seaborn
```

## Installing Jupyter Lab
```
conda install conda-forge::jupyterlab
```

### PyTorch
Please, also install PyTorch using the following [link](https://pytorch.org/get-started/locally/) and insturctions. Once you entered your system details the install command might look something like this:

```
conda install pytorch torchvision torchaudio cpuonly -c pytorch
```

## Verifying the Installation
After installation, you can verify that everything is set up correctly by checking the installed package versions. For example:

```
python --version
pip list
```

## Next Steps
Once your environment is set up and ready, you can proceed to the course content. Make sure to always activate your ml4proteins environment when working on the course materials.

Happy Learning!
