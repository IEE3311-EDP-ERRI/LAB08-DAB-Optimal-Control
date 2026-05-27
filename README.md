# LAB08-DAB-Optimal-Control
This laboratory is designed to follow a process to obatin an optimal LUT which stores duty cicles and phase shift to minimize RMS current for a certain operational point. <br>

You will find [here](https://github.com/IEE3311-EDP-ERRI/LAB08-DAB-Optimal-Control/blob/main/3_DAB_control_TPS.plecs) the simulation file. This Simulation calls this [c-file](https://github.com/IEE3311-EDP-ERRI/LAB08-DAB-Optimal-Control/blob/main/DAB_210_130a200_2p5kw_zvs_1.c) that contains the optimal Lookup Table (LUT) . This table contains the optimal solutions for D1, D2 and phase-shift, which minimizes the RMS current. <br>

Also, [this](https://github.com/IEE3311-EDP-ERRI/LAB08-DAB-Optimal-Control/blob/main/DAB_Optimization_Files.zip) zip file contains all the codes for formulation and solution of the optimization problem for the DAB optimal design proceess and LUT obtaintion.<br>
