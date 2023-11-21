# Production data for WRP AFAL

This repository is for the related data in paper **"An evolutionary knowledge transfer framework for solving workgroup reconfiguration problem in aircraft final assembly"**.

W1.json-W5.json represent the task precedent constraint of five workstations in A1. Each element of the global list of each JSON file is the constraint information for a sub-workstation, represented using a dictionary. Each key-value pair of the dictionary represents a task and its set of predecessors. In the case of W1.json, for example, for task T1_1_1, T1_1_18 is its predecessor task.

W1_info.json-W5_info.json represent the detailed processing information of each workstation task, including workgroup, number of workers, processing time and task weight. Each element of the global list of each JSON file is the processing information of a sub-workstation, which is represented using a dictionary. Each key-value pair of the dictionary represents a task and its processing information. Taking W1.json as an example, for task T1_1_1, the index of its required workgroup is 2, the number of required workers is 1, the processing time is 1 unit, and the task weight is 4.
