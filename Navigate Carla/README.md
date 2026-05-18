# How to navigate in CARLA towns



In this directory there is a python script to navigate through CARLA simulated environment. You can used this script to explore CARLA town and decide you desired location for testing. The code logic is as follows: 



* **0. It is necessary to: A. `initiate a running CARLA server`; B. `Activate opencda conda env`;  before running this script.** 
* **1. Connect to the current CARLA simulation server, and load the desired CARLA map.**
* **2. Read all existing CARLA waypoints all print their index permanently on the screen.** 
* **3. Tick the simulation once to display all the information**.
* **4.Use the keyboard (i.e., W,S,A,D) and the mouse to control the viewing angle. Record the desired spot's transformation for your own usage.**
* FYI: If you read this script, it's basically fully based on the [CARLA Python API](https://carla.readthedocs.io/en/0.9.14/python_api/). Feel free to navigate the official CARLA guide to modify this script, or even opencda (locally). It is also a good idea to use `Ctrl+F` or the search bar to find useful APIs that you need.  

   





