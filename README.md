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
Output:
Average flow rate: L/s
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
Testing:
### Test 1
-Volume (L): 72 
- Time (s): 8
- Expected Flow Rate (L/s): 9
- Actual Flow Rate (L/s): 9
- Result: Pass
### Test 2
Volume (L): 56
- Time (s): 4
- Expected Flow Rate (L/s): 14
- Actual Flow Rate (L/s): 14
- Result: Pass
At first, what mattered most was knowing all the variables at play. Especially knowing the formula given to us, I needed to make sure that with easier implementation, to shower the step where input strings such as volume and time were converted into float values ebfore running the calculations. Now having run the code into the actual Python proccesor like Thonny, it had shown the corrected results I wanted through the two test cases.
