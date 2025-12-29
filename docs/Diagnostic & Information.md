# DIAGNOSTIC & INFORMATION

The Diagnostics & Information window can be used to view and clear Diagnostic Trouble Codes (DTCs).

## Reading DTC's

1. Physically connect your laptop to the ECU with an Ethernet cable.

2. Open VCM Live.

3. Turn the vehicle ignition to a position other than OFF. (The engine can be running or stopped. But, the vehicle must supply power to the ECU.)

4. Click the ![](connect_to_vehicle_icon.png) icon in the toolbar to open a data connection to the ECU.

5. Click ![](dtc_icon.png). The Diagnostics & Information window appears.
![](diagnostics.png)

6. Click **Read DTCs**. VCM Live will query the ECU for diagnostic information. When finished, any DTCs detected will be listed at the top of the window.

## Clearing DTC's 

1. Establish a data connection to the ECU.

2. Click ![](dtc_icon.png). The Diagnostics & Information window appears.

3. Click **Clear DTCs** to tell the ECU to clear the reported DTCs.

## Critical DTC's

Whenever a critical DTC is detected by the ECU it will send the car into limp mode if you are driving reducing the power to 20%. If a critical DTC is detected by the ECU while the engine is off all fuel and spark will be shut off until all critical DTCs are resolved.
![](Critical DTCs.png)

<a href="#" class="top-button" title="Return to top">↑</a>