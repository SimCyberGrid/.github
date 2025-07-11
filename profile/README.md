## Overview
In this project we develope an open-source co-simulation framework for microgrids to realistically model cyberattacks on distributed energy networks and their communication infrastructure, 
supporting research and standardization for resilient, secure smart grids. For this we include a hardware in the loop architecture to combine current hardware with the simulator architecture.

## Background
The energy transition (“Energiewende”) requires the large-scale integration of renewable, and thus variable, energy sources into the energy system. This leads to highly decentralized supply
processes, which are further complicated by the spatial and temporal variability of renewable energy availability. The fundamental challenge is the continuous balancing of energy generation 
and consumption within short, defined intervals: ideally, energy is consumed at the low-voltage level where it is produced, or transferred to neighboring cells. Dynamic pricing models, for 
example, can help maintain this balance and minimize the need for cross-regional energy balancing. These local, decentralized energy regulation and market platforms are referred to as 
microgrids — physical low-voltage segments that will be managed by intelligent local network transformers.

A particular challenge arises from the system’s decentralization and the associated high communication requirements. Traditional isolated communication structures, such as ripple control 
technology, are expected to become insufficient, making communication via the internet or even wireless 5G/6G technologies necessary. However, these technologies are harder to monitor and 
secure than legacy systems and introduce significant cybersecurity risks. As critical infrastructure, microgrids require special protection.

## Project Goals
This project aims to develop advanced monitoring and security procedures for microgrids. At its core, the project will create a co-simulation framework that models both the electrical, 
decentralized grid (as seen from a future grid control center) and the internet (which is vulnerable to cyberattacks). The system will be tested and optimized using realistic virtual 
cyberattacks.
