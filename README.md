# mc_cnf_control
Composite Nonlinear Feedback for PX4

Implementation of a composite nonlinear feedback (cnf) attitude controller for px4.
https://ieeexplore.ieee.org/document/7576819
CNF allows for quick settling time and no overshoot by smootly varying damping as the error decreases.

Instructions:
1. Download px4 v1.8.0 from https://github.com/PX4/Firmware
2. Clone this repo
3. Rename mc_cnf_control to mc_att_control and copy into PX4/Firmware/src/modules/mc_att_control
4. Build px4
