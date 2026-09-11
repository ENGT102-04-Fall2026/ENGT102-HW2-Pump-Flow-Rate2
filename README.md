# ENGT102-HW2-Pump-Flow-Rate2
A Pump and Flow Calculator
Inputs: 
Volume transferred, measured in Liters(L)
Elapsed Time: measured in seconds(s)
Process:
Have the user enter the volume transferred in Liters
Again, have the user enter the elapsed time in seconds
Convert both of the entries to numeric float values with float
Calculate the average volumetric flow rate using the formula: 
Flow rate (L/s) = Volume transferred (L)/ Elapsed time (s)
Pseudocode Here:
START
DISPLAY "Enter the volume transferred (L):"
Input(volume_input)
SET volume = CONVERT (volume_input) to float
DISPLAY "Enter the elapsed time (s): "
Input (time_input)
SET elapsed time = CONVERT (time_input) to float
SET flow_rate = volume / elapsed_time
DISPLAY "Average flow rate:{flow_rate} L/s" 
END
