# 5G-Network-Slicing

# Introduction
5G widely defines network slicing concept which aims to provide different and separate dedicated logical networks that can be customized to respective services. All slices under a cloud infrastructure are put together with their different requirements, e.g. bandwidth, latency

The purpose of this project is to provide a simulation suite for a network consisting of base stations and clients that possible scenarios of 5G can fit into and make analysis of different concepts easier.

# Approach
Discrete event simulation
Using Python 3.7, Simpy, Matplotlib, KDTree
YAML for reading input configurations
Asynchronous programming
# Definitions:
Clients: Simulation consumers. Generates consume requests by given distribution parameters.
Slices of Base Stations: Simulation resources.
Input
Settings
# settings:
  simulation_time: 100 # in seconds
  num_clients: 100
  limit_closest_base_stations: 5 # how many base stations stored in a client instance
 
