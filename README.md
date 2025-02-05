# Labcraft
A Digital Physics Lab in a Blocky Voxel World

[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)


# Dependencies:
## On Linux: 
Labcraft uses python 3.6:
```bash
sudo apt-get install python3
```

## On Windows:
1. Check Your Python version from the Windows CMD or PowerShell:
``` 
python --version
```
If Python 3.6 or newer is already installed, you may skip to the [Ursina installation](https://github.com/quickMaffs44/labcraft/blob/main/README.md#ursina).

2. Download and run the installer from Python.org's [Downloads page for Windows](https://www.python.org/downloads/windows/)


## Ursina:
Labcraft is built on the Ursina engine (https://www.ursinaengine.org)
To install Ursina use pip:
``` bash
pip install ursina
```

Or on Windows CMD/PowerShell:
```CMD
python -m pip install ursina
```

#### Troubleshooting:
If you run into an error concerning a ".deleteme" file, just re-run the installation command.

# Running:
To run, simply:
```bash
python3 labcraft.py
```
Or:
```bash
python labcraft.py
```

# Manifest:
- README.md:
  The file you are currently reading.

- labcraft.py:
  The main labcraft code.

- assetTest.py:
  A little script to test new models and textures.

- sims.py:
  Methods that control the various simulations in the world. Might change
  this later as there becomes more simulations.

- assets:
  Folder that contains all of the models, textures and audio files.

