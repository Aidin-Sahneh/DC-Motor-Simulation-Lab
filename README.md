DC Motor Simulation in MATLAB & Simulink
========================================

This repository contains the simulation models and final report for the "Electric Machines Laboratory 1" course at K.N. Toosi University of Technology.

Project Overview
----------------

This project presents a comprehensive study and simulation of four major types of DC motors. The goal is to understand and compare the dynamic behavior of each motor using different modeling techniques within the MATLAB & Simulink environment.

The key deliverable is a comparison of three distinct modeling approaches:

1.  **Block Diagram Modeling:** Using transfer functions derived from the fundamental motor equations.

2.  **Simscape Physical Modeling:** Using realistic components from the Simscape Electrical™ library.

3.  **Built-in DC Machine Block:** Using the pre-built, abstracted block from Simscape's Specialized Power Systems library.

### Motor Types Simulated

-   Separately Excited DC Motor

-   Permanent Magnet DC Motor (PMDC)

-   Shunt-connected DC Motor

-   Series-connected DC Motor

This project and its comparative methodology were directly inspired by the 2021 IJPEDS publication:

> **"Detailed modelling and simulation of different DC motor types for research and educational purposes"** by Saif S. Sami, Zeyad Assi Obaid, Mazin T. Muhssin, and Ali N. Hussain.

Repository Structure
--------------------

```
DC-Motor-Simulation-Lab/
│
├── .gitignore
├── LICENSE
├── README.md
│
├── Report/
│   └── Electric_Machines_Lab_Report.pdf
│
└── Simulations/
    │
    ├── Separately_Excited_Motor/
    │   ├── setup_params_separately_excited.m
    │   └── ... (all .slx files)
    │
    ├── Permanent_Magnet_Motor/
    │   ├── setup_params_pmdc.m
    │   └── ... (all .slx files)
    │
    ├── Shunt_Connected_Motor/
    │   ├── setup_params_shunt.m
    │   └── ... (all .slx files)
    │
    └── Series_Connected_Motor/
        ├── setup_params_series.m
        └── ... (all .slx files)

```

How to Use This Repository
--------------------------

1.  **Clone the repository:**

    ```
    git clone [https://github.com/Aidin-Sahneh/DC-Motor-Simulation-Lab.git](https://github.com/Aidin-Sahneh/DC-Motor-Simulation-Lab.git)

    ```

2.  **Open MATLAB.**

3.  **Navigate** to one of the simulation folders (e.g., `Simulations/Permanent_Magnet_Motor/`).

4.  **Run the setup script (`.m` file)** first. This is critical as it loads all necessary parameters (e.g., $r_a$, $L_{AA}$, $J$, $B_m$) into the MATLAB workspace.

5.  **Open** any of the `.slx` Simulink models (e.g., `simscape_model_PMDC.slx`) and run the simulation.

Course Details
--------------

-   **Course:** Electric Machines Laboratory 1

-   **Institution:** K.N. Toosi University of Technology

-   **Instructor:** Dr. Naghdi Moradi

-   **Student:** Aidin Sahneh