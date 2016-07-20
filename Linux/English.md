User FAQ for [PokemonGo-Map](https://github.com/AHAAAAAAA/PokemonGo-Map) on `Linux`.

Prepare
========
Open **Terminal** and execute following instructions:

Update repositories: `sudo apt-get update`.

Install Python 2.7.x:

  &nbsp;`sudo add-apt-repository ppa:fkrull/deadsnakes`
  
  &nbsp;`sudo apt-get update`
  
  &nbsp;`sudo apt-get install python2.7`
  
Install Pip: `sudo apt-get -y install python-pip`.

Install Git: `apt-get install git`.

Clone [PokemonGo-Map](): `git clone https://github.com/AHAAAAAAA/PokemonGo-Map.git`.

Go to cloned folder: `cd PokemonGo-Map`.

Install dependencies: `pip install -r requirements.txt`.

Use
======

To use open **Terminal** and execute following instructions:

Go to project folder: `cd PokemonGo-Map-master` (may vary, paste here path to cloned repositary).

Start Flask-server: `python example.py -u myUsername -p myPassword -l "Area where to look for pokemon" -st 5`.

Then open your browser and go to `127.0.0.1:5000`.

If you need to auth with Google account use flag `-a google`. If you need to auto-update pokemon map use flag `-ar 5` (5 seconds). Also look for other flags in [base project's readme](https://github.com/AHAAAAAAA/PokemonGo-Map).
