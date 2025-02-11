# BBN-dice-simulation
Dice simulation program for BBN (a VTR game)

Code written by kraken05doo, licensed under GNU GPL v3.0

## How to use
Step 1 - download the code (click on the green button "Code", then click "Download ZIP") and extract the ZIP file.

Step 2 - navigate to the folder in your downloads.

Step 3 - run the file "bbnDiceSimulator.exe". It will open a terminal, where you input the desired number of trials, pool, and number of rolls per trial. It will take <1s for 10^6 trials.

Step 4 - run the file "grapher.exe". It will open a terminal and take about 20 seconds.

Step 5 - there will now be a file in the folder called "BBN_successes_distribution.png", which is a histogram of the simulated data.

## Source code
The source code for these programs can be found in the folder "bbnDiceSimulatorSourceCode". The simulator is written in C++ and the grapher in Python. If using programs such as Spyder to test the Python script, I suggest commenting out the line "matplotlib.use("AGG")", as Spyder's default backend for matplotlib works better in Spyder.
