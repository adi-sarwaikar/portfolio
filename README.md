# Adi's Engineering Portfolio

## Projects
### Unmanned Aerial Systems – Air Force Research Laboratory
- The Emergency Access and Ground-Link Explorer (EAGLE)
  - Worked with CAD software to brainstorm/design drones to compete in the NIST competition
  - Presented work/research in the Fall Undergraduate Research Expo

Page 396 of [https://www.purdue.edu/undergrad-research/conferences/fall/archive/documents/FallExpo_Abstracts2024.pdf](https://www.purdue.edu/undergrad-research/conferences/fall/archive/documents/FallExpo_Abstracts2024.pdf)
- Technical Skills Used:
  - CAD (Autodesk Fusion 360)
  - CAE (Autodesk Fusion 360)
  - Software Engineering (Python)

### Airfoil Angle of Attack Optimizer
- MATLAB asks user which airfoil they would like to analyze
- Creates `commands.inp` which is a list of commands for XFOIL
- These commands are then passed into XFOIL resulting in the following process taking place
![AOA_xfoil](/assets/img/angle_of_attack_xfoil.png)
- XFOIL returns the coefficients of lift and drag at the various angles of attack as `output.txt`
- MATLAB parses the data from the text file and finds optimal lift, optimal drag, and optimal lift-to-drag ratio
- Results are displayed in the following graphs:
![AOA_graphs](/assets/img/angle_of_attack_graphs.png)
- Technical Skills Used:
  - Physics (Airfoils)
  - Simulation Software (XFOIL)
  - Software Engineering (MATLAB, XFOIL)
  - Data Presentation (MATLAB)

### Semi-autonomous 3D Printed Prosthetic Hand
- Designed a hand with CAD software that could mimic the movements of a normal hand.
- The design was 3D printed and assembled with screws and nuts at each joint.
![3D_Hand_CAD](/assets/img/3d_hand_cad.png)
- To move each joint fishing lines was tensioned by a multitude of stepper motors. 
- Stepper motors were connected to an Arduino Mega which would take input from a computer. 
- The computer uses Google's machine learning algorithm to identify hand symbols through the camera. 
- The camera identifies a hand sign and sends the hand sign to the Arduino Mega.
- Arduino Mega drives the stepper motors to their specified values.
- The motors pull the hand into the same position as the camera has identified.
![3D_Hand_Real](/assets/img/3d_hand_real.png)
- Technical Skills Used
  - CAD (Autodesk Fusion 360)
  - CAE (Autodesk Fusion 360)
  - Software Engineering (Arduino C, Python)
  - Machine Learning/AI (Python)

## Courses
### ENGR 133 - EPICS Transforming Ideas to Innovation
- Data analytics (calculations, descriptive statistics, histograms, probability, charts, and regression).
- Communication (reports, peer review, and information literacy).
- Teaming (team dynamics, team member roles, diversity, and code of cooperation).
- Team projects (modeling and design).
- Excel basics (calculations, importing data, relational operators, plotting data).
- Python basics (scripts, data types, importing data, relational operators, logical operators, plotting data, user-defined functions, selection structures, while loops, for loops, and nested loops).
- MATLAB basics (calculations, scripts, importing data, publishing code, relational operators, logical operators, plotting data, user-defined functions, selection structures, while loops, for loops, and nested loops).

### ME 270 - Basic Mechanics
- Vector operations, forces and couples.
- Free body diagrams, equilibrium of particles and rigid bodies.
- Distributed forces.
- Centers of gravity and centroids.
- Friction.
- Trusses, frames, and machines.
- Internal reactions resulting from axial, shear, torsional, and bending loading.
- Stress and strain analyses and elementary failure criteria.

### MFET 163 - Graphic Communication & Spatial Analysis
- Effectively utilize Siemens NX to model to design for change by infusing design intent through the use of dimensioning schemes, parameters, and design tables
- Worked with a Product Data Management (PDM) system (Siemens Teamcenter) to support design, collaboration, and geometry re-use to simulate an industry PLM setting
- Followed Engineering Change Process leveraging Engineering Change Orders (ECO) and approval workflow in PDM to submit all work for the course for evaluation and feedback
