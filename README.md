# MBTA-simulation
MBTA simulation with self-created Double Linked List &amp; queue

You have been tasked to run a simulation of the Red Line for the MBTA. This will entail populating the stations with trains and passengers from text files, run the simulation, and print out a log that includes the status of the railway’s stations and the movement of trains and passengers.

Basic Idea:
You will be given three text files from which you will create the stations, the trains, and the passengers. Each station will maintain queues for passengers who are waiting to travel. Since a station can load and unload passengers onto only 1 train at a time, it will also have queues for any additional trains who have arrived at the station. Trains can hold a limited number of passengers and can only travel in one direction at a time.

The 3 data structures classes and 5 MBTA related classes are described in detail below. You must implement the following methods following these exact signatures. Furthermore, some of these classes include specific fields. You must also include these in your implementation and leave them as public.
