wsnScenarios
============

A repo containing the wireless sensor network topologies from a study.

Each problem instance is represented by a distance file that allows for the plotting of the topology, and a dot file that outlines the links with their node-to-node reliabilities according to the Rayleigh interference model.

Each network distributes the sensors uniformly at random in a circle around a center point.

The networks are encoded as exemplified in "1_n200_l0.5_r100_s4_wsn.dot":
* scenario id 1 for a network of size 200 ("1_n200")
* the radius of the network is 100 ("r_100")
* half of the nodes are located in the inner circle of radius 0.5 of the radius ("l_0.5")
* 4 sinks according to "s4" (optional, otherwise 1 sink assumed in the center, if missing)

The amount of channels for scheduling to be utilized can be decided individually of the outlined topology.
