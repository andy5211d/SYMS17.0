The SYMS17.0 Control PCB (2000802731) used in a number of central heating and combi boilers.  This board has voltages that WILL KILL YOU if you touch the HV DC side.  

Included are details of some capacitors that may require changing if the board is faulty.  I change the five main capacitors as a matter of course.  A fault in the HV side (blown switcher) will often take out tracks and the through-hole plating!  

Also included are relevant voltages around the PCB.  Check your board as this is just my guess as to the details and circuit snippets!  

This is an unregulated SMPS, in that there is NO feedback between the secondary voltages and the switcher drive.  The main LV DC is around 40V with the boiler quiescent, (note the smoothing capacitors for this are 35V working!), and during operation drops to around 30V dependent upon fan speed.  The second LV DC is around 12V dropping to 9V dependent upon fan speed.  Two other voltages, 18V and 5V are used and these are from regulators and thus stable irrespective of the fan speed.  There are probably other derived voltages!  The opto coupler, U102, provides the controlling micro with the AC input (and perhaps HV DC value), or at least that's my assumption from tracing tracks on the board!

I have noticed at least three versions of the board (see number at the bottom left corner). As best I can tell variations are around the regulator U503, some boards seem to omit this and newer it has been designed out.  