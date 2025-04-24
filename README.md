## How to install kokoro and set-it up on linux/wsl

First lets intall all the pre-requirements for linux, this also works on WSL2!
```
sudo apt-get update
sudo apt-get upgrade
sudo apt-get install gcc
```
Now let's create a new env to install kokoro inside that env, this is optional but it's a good practice, I recommend using miniconda.
```
conda create -n kokoro python=3.9
conda activate kokoro # Activate a conda or venv where is going to be installed kokoro
```
Inside your new env let's install *kokoro* and *soundfile* to make things work!
```
pip install kokoro
pip install soundfile
```
