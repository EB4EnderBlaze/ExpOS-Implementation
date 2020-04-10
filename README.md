ExpOS implementation by Ruturaj Malavade

================================================================================================================

Completed:
Upto Stage 27 of roadmap

Not completed:
Stage 28 of roadmap

================================================================================================================

Code is located in various places.

EXPL code is located in expl/samples (EXPL code mostly consists of programs that will be used to test XSM)
SPL code is located in spl/spl_progs
SPL Testing code is located in spl/spl_progs/testing

================================================================================================================

To run:
Go into xfs-interface folder, run ./xfs-interface, then run the following 3 commands:

	fdisk
	run runfile.txt
	exit

Then, go to the xsm folder and run ./xsm

Then, login with username root and password root, then run various files that can be run, or enter "Shutdown" without quotes to shut down the simulator.

================================================================================================================

The output of some of the files being run is located in the "screenshots" folder.

Some of the files tested (Screenshots in screenshots folder):

init_odd.xsm : prints odd numbers from 200-300
even.xsm : prints even numbers from 100-200
gcd.xsm : takes in two numbers as input, returns their GCD
