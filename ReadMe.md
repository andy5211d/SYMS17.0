The SYMS17.0 Control PCB (2000802731) used a number of gas boilers.   Includes details of some
capacitors that may require changing and relevant voltages around the PCB.  Check your board as
this is just my guess as to the details and circuit!  

This is an unregulated SMPS, in that there is NO feedback between the secondary voltages and the
switcher drive.  The main LV DC is around 40V with the boiler quiescent, (note the smoothing
capacitors for this are 35V working!), and during operation drops around 30V dependent upon fan
speed.  The opto coupler U102 provides the controlling micro with the AC input and HV DC values,  
or at least that's my assumption from tracing tracks on the board!  

I have noticed at least three versions of the board but seem interchangable in some boilers (see
bottom left courner). Most variations are around the regulator U503 which new boards seem to
omit or have been designed out of the layout.  