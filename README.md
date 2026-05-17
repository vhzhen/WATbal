# WATbal (Proof of Concept)
WATs your balance? For students of the University of Waterloo, check your Flex Dollars using Playwright and Python, needing Duo Mobile Authentication only once!

.py (new)
1. Requires Kivy and Playwright libraries and their dependencies to be installed
* pip install Playwright
* playwright install
* pip install Kivy

2. login to UWaterloo through the external browser popup
3. cookies.json stores your cookies so Duo Mobile Authentication only needs to be completed once




.ipynb (outdated)
1. Input your UWaterloo username (...@uwaterloo.ca) and password to initialize the program
2. cookies.json stores your cookies so Duo Mobile Authentication only needs to be completed once
3. On your first run of the program, use the Duo Mobile app to enter the three-digit number given for initial access
