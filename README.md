# ENGT102-HW2-Pump-Flow-Rate2
A Pump and Flow Calculator
START
DISPLAY "Enter the volume transferred (L):"
Input(volume_input)
SET volume = CONVERT (volume_input) to float
DISPLAY "Enter the elapsed time (s): "
Input (time_input)
SET elapsed time = CONVERT (time_input) to float
SET flow_rate = volume / elapsed_time
DISPLAY "Average flow rate:{flow_rate} L/s" 
