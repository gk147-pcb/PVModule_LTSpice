# Photo-Voltaic Module desiigned on LT Spice
 Designed and simulated a solar cell and a corresponding PV module that consists of 36 cells on LT Spice.
 
# Single Solar Cell Circuit Diagram
![alt text](https://github.com/gk147-pcb/PVModule_LTSpice/blob/main/Single_Solar_Cell.png/?raw=true)
A single solar cell has the equivalent circuit diagram of a current source. In this case, the current source is I1 with a magnitude of 3A with a diode D1 connected in parallel.

# PV Module
![alt text](https://github.com/gk147-pcb/PVModule_LTSpice/blob/main/PV_Module_36_Cells.png/?raw=true)
This is the internal circuit of the PV module consisting 36 individual solar cells by setting the parameter (n = 36)

# PV Module Circuit Diagram for Simulation
![alt text](https://github.com/gk147-pcb/PVModule_LTSpice/blob/main/PV_Module.png/?raw=true)
Above is the circuit diagram of the PV module itself which is used to carry out the simulation on DC voltage sweep. Below are the V-I Characteristics generated from the simulation.

# I-V and Power-Voltage Characteristics
![alt text](https://github.com/gk147-pcb/PVModule_LTSpice/blob/main/IV_Curve.png/?raw=true)
![alt text](https://github.com/gk147-pcb/PVModule_LTSpice/blob/main/Power_Voltage_Curve.png/?raw=true)

These curves are for 6 different values of input current. You can see that the curves verify the functioning of a PV module and hence, conclude that the equivalent circuit of a PV module can be represented as a current source with a diode in parallel.
 
