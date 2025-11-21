## Programmer Assessment Q4

This repository contains a broken web app built with Dash. Please follow the tasks below.

Tasks:
1. Clone this repo to your machine.
2. Fix missing dependencies and fill authors section in `pyproject.toml`.
3. Fix bugs prevent the app `main.py` from running.
4. Change port the app ruuning on to `10030`.
5. Commit you changes.
6. Update `README.md` with a instruction
   1. Assuming the user has a fresh minimum Linux installation with no python.
   2. Setup python and virtual environment for this app, remember to use the fixed `pyproject.toml`.
   3. How to run this app and how to access it without portforwarding.
7. Push all the changes to your own repository on Github, and provide a link to your own repo in your submission in the last.


Instruction:
1. Install Python
   1. sudo apt update
   2. sudo apt install -y python3.12 python3.12-venv python3-pip
2. Create a virtual environment in assessment-debugging
   1. python3.12 -m venv venv
   2. source venv/bin/activate
3. Install the dependencies using pyproject.toml
   1. pip install .
4. Run main.py to start the app
5. Access the app through http://<your_ip>:10030/


