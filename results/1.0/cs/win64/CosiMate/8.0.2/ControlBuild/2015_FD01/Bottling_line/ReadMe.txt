Tool:
  CosiMate,version 8.0.2

Model:
 CoSimulation\win64\CosiMate\8.0.2\ControlBuild\2015_FD01\Bottling_line\Bottling_line.fmu

Files:
 -'{FMUName}_Out.csv' - The result from a simulation of the model in-case of a successful simulation.
 -'{FMUName}_Exception.txt' - The description of the error in-case of a failure.
 -'{FMUName}.gcn' - The Graphical CosiMate Netlist
 -'{FMUName}.xcn' - The Interface XML Description
 -'{FMUName}_ref.csv' - Input data ref 
 -'{FMUName}_in.csv'  - Input data for cosimulation
 -'{FMUName}.ixd' - Interface XMl Description of the FMI Model
 -'IOs.mdl' - Simulink Model for co-simulation and results comparaison
 -'IOs.ixd' - Interface XMl Description of the Simulink Model
 -'{FMUName}_results' - Screen shot of Simulink scope results
 -'{FMUName}_ref.opt' - Solver time and tolerance information

Simulation information : 
 - Variables input are those from {FMUName}_in.csv
 - Variables output are those from {FMUName}_ref.csv
 - Simulation solver settings are those specified in the {FMUName}_ref.opt


Tested with MATLAB version: 8.4.0.150421 (R2014b)
