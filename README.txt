README
@autor : Thibault Charlottin Licit Eco7 University Gustave Eiffel, ENTPE Lyon France
@contributor : Christine Buisson Licit Eco7 University Gustave Eiffel, ENTPE Lyon France
Code under licence EPL 2.0


This script is devoted to realize simulations corresponding to a wide variety of freeway mixed (Automated Cruise Control and Human Driven Vehicles) traffic 
situations and to cluster them with three classical clustering methods. The script is working on top of the Sumo code that you must install 
(in the Windows version) before processing the current script.

The first part allows you to create simulations on SUMO with two car-following models and to compute them. In the second and third parts you create indicators, analyse and cluster obtained data. 
- 1st part: file simulation using Traci module
- 2nd part: indicators definition and computation
- 3rd part: indicator clustering and plot editing
SUMO can be downloaded for windows versions (the only to work with this code) at https://sumo.dlr.de/docs/Downloads.php

Warning 1 the Traci librairies are Windows based, the simulation section won't work on Mac
Warning 2 this code was not tested on Linux distributions

How to use the code
! Do not change any file path in the folder that contains the code and the inputs !

To do: 
-Change global_path value (cell 3) according to the path you putted the files in
-Change sumoBinbary accordingly to your local sumo path (cell 3)
-Change the paths (lines 18 and 19) in the export_sumocfg function (cell 7)

Misc:
When executing the code for the first time please run all the import the inputs cells before running the simulation cells 
You must restart the kernel if exiting during a simulation so that the traci module can reinitialize



