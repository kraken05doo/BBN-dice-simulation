# BBN-dice-simulation
Dice simulation program for BBN (a VTR game)

Code written by kraken05doo, licensed under GNU GPL v3.0

## How to use
Step 1 - navigate to the folder "bbnDiceSimulation" on this page, which should contain 3 files - "bbnDiceSimulator.exe", "grapher.exe", and a third file not needed for this.

Step 2 - click on each file and click on the download button (an arrow pointing down next to a button named "Raw" in the top right hand side).

Step 3 - create a new folder somewhere on your computer (e.g. on your Desktop), locate these files in your downloads folder and copy them to the new folder.

Step 4 - run the file "bbnDiceSimulator.exe". It will open a terminal, where you input the desired number of trials, pool, and number of rolls per trial. It will take ~0.1s for 10^6 trials.

Step 5 - run the file "grapher.exe". It will open a terminal and take about 20 seconds.

Step 6 - there will now be a file in the folder called "BBN_successes_distribution.png", which is a histogram of the simulated data.

## Source code
The source code for these programs can be found in the folder "bbnDiceSimulatorSourceCode". The simulator is written in C++ and the grapher in Python. If using programs such as Spyder to test the Python script, I suggest commenting out the line "matplotlib.use("AGG")", as Spyder's default backend for matplotlib works better in Spyder.
