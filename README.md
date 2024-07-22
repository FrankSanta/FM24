# Formal Analysis of Search-and-Rescue Scenarios
### Search and Rescue Scenarios
Search and rescue (SAR) is the act of searching and providing help to people in imminent danger through specialized personnel and specialized vehicles or devices.
In our project, we examine a SAR scenario set in a room with a raging fire. Within this room, there are various types of actors: civilians, who may either need assistance or be capable of helping others (referred to as zero responders); first responders, who are trained professionals providing aid; and drones, which patrol the area to support rescue efforts. The objective of the SAR operation is to ensure the safety of as many civilians as possible within a designated time frame.
### Objective
Our objective is to implement a timed automaton that simulates the evolution of a search and rescue scenario to check how the decision policies of the actors affect the success of the operation. To do so we implemented both a deterministic and a stochastic model in UPPAAL (v 5.0.0) and tested the properties of the model on different scenarios. All the details about the assumptions and the detail about the implementation are discussed in the report.
### How to run
1. Install [Uppaal](https://uppaal.org/) v5.0.0. 
2. Pull the repository and open FM_project.xml or FM_project_stochastic.xml to load the deterministic or the stochastic model.
3. Verify the properties using the Uppaal verifier.
   
To change the scenario:
1. Open an existing model file in the Test_Cases folder or generate a new one running the Test_generator.ipynb notebook.
2. Open the .txt file and copy-paste its content between the delimiters inside global Declarations.
