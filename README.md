Thermal and Dynamic Modelling of Permanent-Magnet Synchronous Motors (PMSM) Driven Electric Vehicle Powertrain with Dual-Loop Control Strategy

📌 Project Overview
This repository contains the simulation models, scripts, and datasets associated with the publication: "Thermal and Dynamic Modelling of Permanent-Magnet Synchronous Motors (PMSM) Driven Electric Vehicle Powertrain with Dual-Loop Control Strategy."
The project focuses on the comprehensive modeling of a PMSM-based electric vehicle (EV) powertrain. It features a robust dual-loop control strategy designed to optimize motor performance while accurately capturing thermal and dynamic behaviors under various drive cycles. This repository provides a high-fidelity framework for analyzing simulation metrics, model accuracy, and real-time powertrain efficiency.

⚙️ Software Requirements
To run the simulations and execute the scripts, the following environment is required:
MATLAB (R2023a or newer recommended)
Simulink
Simscape™ (specifically Simscape Electrical for motor and inverter modeling)
Control System Toolbox

📂 Repository Structure
/models/: Contains the core Simulink (.slx) files.
PMSM_Powertrain_Main.slx: The primary system-level EV powertrain model.
Dual_Loop_Controller.slx: The isolated subsystem for the dual-loop control strategy (speed and current control).
Thermal_Network.slx: The Simscape-based lumped-parameter thermal network for the PMSM.
/scripts/: Contains the MATLAB (.m) initialization and plotting scripts.
init_parameters.m: Loads all motor, vehicle, and thermal parameters into the workspace prior to simulation.
plot_simulation_metrics.m: Generates high-fidelity comparative plots for thermal dynamics, torque ripple, and efficiency.

/data/:
drive_cycles/: Contains standard drive cycle profiles (e.g., WLTP, NEDC) used to test the powertrain.
results/: Exported simulation data for model fidelity analysis and validation.

🚀 Key Features
High-Fidelity PMSM Model: Captures both electrical and mechanical dynamics crucial for EV applications.
Advanced Thermal Modeling: Integrates a detailed thermal management simulation to monitor temperature variations in the stator, rotor, and windings during operation.
Dual-Loop Control Strategy: Implements an outer speed loop and an inner current loop for precise torque regulation and field-oriented control (FOC).
Performance & Fidelity Metrics: Built-in capabilities to thoroughly evaluate simulation accuracy against theoretical baselines and evaluate key metrics.

💻 How to Run the Simulation
Clone this repository to your local machine:

Bash
git clone https://github.com/some-funAPI/EV-PMSM-Thermal-Dynamic-Model.git
2.  Open "MATLAB" and navigate to the cloned repository folder.
3.  Run the initialization script by typing `init_parameters` in the Command Window. This will load all necessary variables into your workspace.
4.  Open `models/PMSM_Powertrain_Main.slx` in Simulink.
5.  Select your desired drive cycle within the simulation environment and click "Run".
6.  Once the simulation completes, run `scripts/plot_simulation_metrics.m` to visualize the dynamic and thermal responses.

📝 Citation
If you use these models or scripts in your academic work, please cite the original paper:
Somefun, T. E., et al. (2026), Thermal and Dynamic Modelling of Permanent-Magnet Synchronous Motors (PMSM) Driven Electric Vehicle Powertrain with Dual-Loop Control Strategy. Frontier in Energy Research. DOI: 

✉️ Contact:
Dr. Tobiloba Emmanuel Somefun, 
Email: somefte@unisa.ac.za , 
Institution: University of South Africa (UNISA)
