# auvlib-tutorial

auvlib tutorial for ODF Workshop in Gothenburg 2019.

These are instructions for setting up the requirements for the tutorial. You will be handed out a USB stick containing the notebooks in this repo + data and, in the case of windows, auvlib itself. Note that the the last notebook `training.ipynb` requires pytorch and visdom, which we do not expect you to install (it is especially hard on windows).

**NOTE**: if you have any problems with the instructions, please [open an issue here](https://github.com/nilsbore/auvlib-tutorial/issues) and I will try to help out.

Network definitions have been adapted from [junyanz](https://github.com/junyanz/pytorch-CycleGAN-and-pix2pix).

## If you just want to follow along

You can actually see the commands and most of the output plots directly in this webpage.
To look at them while I'm talking, just open in order:

1. [parsing.ipynb](https://github.com/nilsbore/auvlib-tutorial/blob/master/parsing.ipynb)
2. [processing.ipynb](https://github.com/nilsbore/auvlib-tutorial/blob/master/processing.ipynb)
3. [training.ipynb](https://github.com/nilsbore/auvlib-tutorial/blob/master/training.ipynb)

## Linux instructions

1. First, follow the instructions from [here](https://github.com/nilsbore/auvlib#dependencies) to compile auvlib, and make sure to add the installed lib folder to your `$PYTHONPATH`.
2. Make sure you have python3 and pip3 installed
3. Install the following python libraries: `jupyter`, `numpy`, `matplotlib`, `Pillow` (e.g. using `pip3 install jupyter numpy matplotlib Pillow`)
4. Optionally, you can also try to install [pytorch](https://pytorch.org/) and `visdom`, with or without GPU support
5. In the workshop session, copy the provided example data and unzip using `unzip auvlib_tutorial_example_data.zip` inside the repo folder
6. To try if it works, go the folder containing e.g. `parsing.ipynb` in the terminal and execute `jupyter notebook`. Try clicking on the `parsing` notebook and execute the first cell by clicking it and pressing `ctrl+enter`

## Windows instructions

### NOTE: this is currently out-of-date!

1. If you do not have python2.7 and pip installed, use [this guide](https://github.com/BurntSushi/nfldb/wiki/Python-&-pip-Windows-installation) to download and install **64-bit python2.7** and pip, and add the proper paths to your environment variables
2. Execute `pip install jupyter numpy matplotlib Pillow`
3. In the BTS tutorial session, you will get a USB stick containing the notebooks from this repo, the data and auvlib. Optionally, if you want a system wide installation of auvlib, you can download it from the [releases page](https://github.com/nilsbore/auvlib/releases)
4. To try if it works, go the folder containing e.g. `parsing.ipynb` in the command prompt and execute `jupyter notebook`. Try clicking on the `parsing` notebook and execute the first cell by clicking it and pressing `ctrl+enter`

## MacOS instructions

1. Find a buddy with a either Windows or Linux
2. Buy her/him a beer and do the tutorial together!
