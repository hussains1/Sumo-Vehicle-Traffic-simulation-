# Sumo-Vehicle-Traffic-simulation-

This is the files which is used to simulate the vehicles in the traffic network. I have used SUMO (Simulation of Urban Mobility) as the main open source for simulating traffic networks. As part of my final year project this was one of the main goals to achieve and to show an analysis of vehicle patterns in the traffic management system in smart city. 

Step 1:
Set up and Download SUMO (https://sumo.dlr.de/docs/Downloads.php)

Step 2:
Once the app is downloaded, click the "open the simulation" button from the top left and open the "Configuration.sumo.cfg" file.

Step 3:
If this does not work, copy all the files and create a new folder called "SumoTest".

Step 4:
Open the folder location and double click the file location and enter "CMD"

Step 5:
When the cmd opens with the correct file path location enter this command to automatically simulate the traffic network:
sumo-gui -c grid3.sumo.cfg --device.fcd.period 100
