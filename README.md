![Release](https://github.com/mikebourbeauart/mb-armada/workflows/Release/badge.svg)
![Documentation Status](https://readthedocs.org/projects/armada-pipeline/badge/?version=latest)](https://armada-pipeline.readthedocs.io/en/latest/?badge=latest)
![alt text](https://github.com/mikebourbeauart/mb-armada/blob/feature/docs/cover_full_github.png?raw=true)

An art asset pipeline for artists

Documentation will live on readthedocs.org. It won't be set up for source release, but it's something to get fixed during beta!

Download the beta now! https://gum.co/YwBqX

Future website: https://www.armadapipeline.org

Discord: https://discord.gg/5jXdtau


Artists
======
*Getting started:*
---------------
**Windows 10 and MacOS**
1. Download the latest release of Armada Pipeline (zip file) [here](https://github.com/mikebourbeauart/mb-armada/releases)
2. Extract it to a safe place on your hard drive
3. `armada_pipeline.exe` is currently both the installer and the actual program.
    After you complete the setup you will use this exe to run the program
4. Double click `armada_pipeline.exe` and enjoy!


Developers
==========

- *Style:* PEP 8
- *Pull Requests:* master and develop branches only

Getting Started
---------------

Development Setup:
1) Install [Python 3.7](https://www.python.org/downloads/release/python-370/)
2) Choose an IDE
    - I use [PyCharm Pro](https://www.jetbrains.com/pycharm/). All instructions will assume you are too 
3) Install Virtual Environment
    - ctrl+alt+s to bring up settings and navigate to project > project interpreter
    - Gear icon > Add 
    - Select Virtualenv Environment > New environment
        - Location = `path\to\armada-pipeline\venv`
        - Interpreter Base = `path\to\Python 3.7\python.exe`
4) Install requirements


Key Modules:

- armada
	- Armada's core package.
- launcher
	- The main file explorer from which all apps are launched.
- marina
	- A mini-launcher that manages software file iteration and resides within the software being utilized.
- atlantis
	- Asset manager that manages asset publishing, importing, and saving.
- utilsa
	- Contains utility classes like the custom logger
