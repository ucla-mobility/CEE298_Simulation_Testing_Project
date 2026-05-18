# CEE 298 Simulation Testing Project

This is the repo for the Simulation Testing project. The project goal is to

* **1\. Recreate a testing scenario** that is listed among the NHTSA challenging dataset.   
* **2\. Test OpenCDA's default autopilot agent** in this scenario.   
* **3\. Generate traffic level performance metrics** for the OpenCDA's default agent. 

This meta file’s intention is to help you streamline the process and break down the task into multiple steps. You are encouraged to experiment with alternative methods, should you have a different approach. Please feel free to contact me (Xu) if you have any questions or need help with anything. The task breakdown is as follows. 

1. ## Read the NHTSA Dataset 

	The NHTSA dataset we used contains a list of scenarios that we selected from the official "Pre-Crash Scenario Typology for Crash Avoidance Research." A [detailed document](https://github.com/ucla-mobility/CEE298_Simulation_Testing_Project/blob/main/NHTSA%20dataset/cee%20298%20scenario%20docs.pdf) is uploaded to the "NHTSA dataset" folder within the repo. The list we are using is summarized in "cee 298 scenario docs.pdf," and the original pre-crash document is also uploaded in the same directory as a reference.

2. ## Review the default CARLA maps (Towns)

   A detailed CARLA map introduction can be found [here](https://carla.readthedocs.io/en/0.9.14/core_map/#the-map). A list of all ten maps can be found [here](https://carla.readthedocs.io/en/0.9.14/core_map/#non-layered-maps). After selecting the desired NHTSA scenario to recreate, you can go through these 10 CARLA towns to select a map to create your scenario. Please note that these 10 towns are built with different emphasis, so select the corresponding map based on your own needs.

3. ## Review the OpenCDA scenario YAML files

   OpenCDA loads the scenario by reading the scenario configuration file. This file dictates all the details in the testing scenario, such as what vehicles are included in the scene, where they are spawned, where they are trying to go, and what their behaviors are. In addition, these files set the OpenCDA in different modes; for example, trajectory analysis can be turned on/off here. All the existing sample scenarios provided in OpenCDA are listed [here](https://github.com/ucla-mobility/OpenCDA/tree/main/opencda/scenario_testing/config_yaml), and their corresponding Python scripts (i.e., [same_name].py) are stored [here](https://github.com/ucla-mobility/OpenCDA/tree/main/opencda/scenario_testing). **It is important to look at these config files and determine what information is needed for your own customized scenario.** 

4. ## Find the desired spots 

   

5. ## Generate the agent and NPC 

   

6. ## Run the experiment 
