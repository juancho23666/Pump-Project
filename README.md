Pump Commands 
Dispense commands
“D, [ml]’ - pump dispenses this specific volume
“D, - [ml]’ - pump dispenses this specific volume in reverse
“D, *” - pump will continuously run
“D, *” - pump will continuously run in reverse
Ex; “D,200” - dispenses 200 ml

Dispense fixed volume over a fixed time
“D, [ml], [min]” - Dispenses this volume over this many minutes
Ex: “D, 2000, 10” - Dispenses 2000ml over 10 minutes

Constant Flow Rate
“DC, [ml/min], [min or *]” - Maintains this flowrate for this much time (* =  indefinitely)
Ex: “DC, 50, 40” - Dispenses 50ml per minute for 40 minutes

Pause and Stop dispensing
“P” - Pause the pumpduring dispensing, send command again to unpause
“X” - Stops dispensing completely

“Invert” - changes dispensing direction of pump

Calibration
“Cal, v” - v = actual volume dispense
Ex: user sends command “D,200” to dispense 200ml, but pump actually dispenses 146.2ml to fix this enter the command “Cal, 146.2”
“Cal, clear” - Deletes all calibration data
