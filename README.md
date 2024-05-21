# DyBatch: Message Prioritization and Priority-driven Dynamic Batch Verification in Large-scale IoV Networks

## Introduction
This repository contains the implementation of the DyBatch scheme, which prioritizes and dynamically verifies messages in large-scale Internet of Vehicles (IoV) networks. It includes scripts for message classification, batch formation, dynamic batch verification, and batch reformation using Jetson Nano, as well as simulations using SUMO and NS-2.

## Directory Structure
/DyBatch
|-- jetson_nano
| |-- msg_classification_batch_formation.py
| |-- dynamic_batch_verification.py
| |-- batch_reformation.py
|-- sumo_simulation
| |-- sumo_simulation.py
| |-- sumo_config
| | |-- jaipur.net.xml
| | |-- jaipur.rou.xml
| | |-- jaipur.sumocfg
| | |-- add_tls.xml
| |-- data
| | |-- sample_data.csv
|-- ns2_simulation
| |-- ns2_simulation.tcl
| |-- traffic_scenario
| | |-- traffic_scenario.tcl
|-- README.md
|-- requirements.txt
|-- LICENSE


## Prerequisites
### Jetson Nano
Ensure Python and required libraries are installed.
```sh
sudo apt-get update
sudo apt-get install python3-pip
pip3 install pandas pycryptodome paho-mqtt



## Required Packedge
pandas

pycryptodome

paho-mqtt
