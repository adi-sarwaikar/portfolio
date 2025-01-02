# Adi's Engineering Portfolio

## Projects
### Unmanned Aerial Systems – Air Force Research Laboratory
- The Emergency Access and Ground-Link Explorer (EAGLE)
  - Worked with CAD software to brainstorm/design drones to compete in the NIST competition
  - Presented work/research in the Fall Undergraduate Research Expo

[Page 396 of https://www.purdue.edu/undergrad-research/conferences/fall/archive/documents/FallExpo_Abstracts2024.pdf](https://www.purdue.edu/undergrad-research/conferences/fall/archive/documents/FallExpo_Abstracts2024.pdf)
### Airfoil Angle of Attack Optimizer
- Used XFOIL to run airfoil simulations at various angles of attack for different NACA 4-digit airfoils
- MATLAB asks user which airfoil they would like to analyze
- Creates `commands.inp` which is a list of commands for XFOIL
- These commands are then passed into XFOIL resulting in the following process taking place
![AOA_xfoil](/assets/img/angle_of_attack_xfoil.png)
- XFOIL returns the coefficients of lift and drag at the various angles of attack as `output.txt`
- MATLAB parses the data from the text file and finds optimal lift, optimal drag, and optimal lift to drag ratio
- Results are displayed in the following graphs:
![AOA_graphs](/assets/img/angle_of_attack_graphs.png)

### Semi-autonomous 3D Printed Prosthetic Hand
- Designed,3D printed, and assembled prosthetic hand-controlled through fishing line and stepper
motors connected to Arduino Mega
- Uses camera and machine learning to identify hand signs of a real hand and replicate them on the
prosthetic

![3D_Hand_CAD](/assets/img/3d_hand_cad.png)

![3D_Hand_Real](/assets/img/3d_hand_real.png)
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
