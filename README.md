# auvlib-tutorial

auvlib tutorial for BTS 2019

These are instructions for setting up the requirements for the tutorial. You will be handed out a USB stick containing the notebooks in this repo + data and, in the case of windows, auvlib itself. Note that the notebook `training.ipynb` requires pytorch, which we do not expect you to install (it is especially hard on windows).

## If you just want to follow along

You can actually see the commands and most of the output plots directly in this webpage.
To look at them while I'm talking, just open in order:

1. [parsing.ipynb](https://github.com/nilsbore/auvlib-tutorial/blob/master/parsing.ipynb)
2. [processing.ipynb](https://github.com/nilsbore/auvlib-tutorial/blob/master/processing.ipynb)
3. [training.ipynb](https://github.com/nilsbore/auvlib-tutorial/blob/master/training.ipynb)

## Linux instructions

1. First, follow the instructions from [here](https://github.com/nilsbore/auvlib#dependencies) to compile auvlib, and make sure to add the installed lib folder to your `$PYTHONPATH`.
2. Make sure you have python2.7 installed
3. Install the following python libraries: `jupyter`, `numpy`, `matplotlib`, `Pillow` (e.g. using `pip install jupyter numpy matplotlib Pillow`)
4. Optionally, you can also try to install [pytorch](https://pytorch.org/) and `visdom`, with or without GPU support
5. Execute `wget --no-check-certificate https://strands.pdc.kth.se/public/AUVLib_tutorial/auvlib_tutorial_example_data.zip && unzip auvlib_tutorial_example_data.zip` inside the repo folder
6. To try if it works, go the folder containing e.g. `parsing.ipynb` in the terminal and execute `jupyter notebook`. Try clicking on the `parsing` notebook and execute the first cell by clicking it and pressing ``ctrl+enter`

## Windows instructions

1. If you do not have python2.7 installed, download the `x86-64 MSI installer` from [here](https://www.python.org/downloads/release/python-2716/) and install python to the default location
2. Before executing any of the following steps (including the tutorial), you need to have executed `set PATH=%PATH%;C:\Python27\Scripts` in the same command prompt. To make this permanent, you could also add this command to your `autoexec.bat` or add it in the graphical environment variables interface
3. Execute `pip install jupyter numpy matplotlib Pillow`
4. In the BTS tutorial session, you will get a USB stick containing the notebooks from this repo, the data and auvlib. Optionally, if you want a system wide installation of auvlib, you can download it from the [releases page](https://github.com/nilsbore/auvlib/releases)
5. To try if it works, go the folder containing e.g. `parsing.ipynb` in the command prompt and execute `jupyter notebook`. Try clicking on the `parsing` notebook and execute the first cell by clicking it and pressing ``ctrl+enter`

## MacOS instructions

1. Find a buddy with a either Windows or Linux
2. Buy her/him a beer and do the tutorial together!
