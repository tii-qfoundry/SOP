# Magnetron Sputtering with DC and RF sources.
> [!NOTE]
> When the AJA Sputterer is turned off, Nitrogen needs to keep flowing until the vaccum turbo pumps have come to a full stop. Then the nitrogen lines need to be manually shut down. Nitrogen must be kept open as long as the vaccum pumps are in use.

> [!WARNING]
> When the substrate holder is heated, it needs to cool down in the vented load-lock chamber until it reaches a temperature below 50C (approximately 30 min) before any additional process is carried.

| Reference | Publication Date | Revision |
|----|----|----|
|QFSOP_0323 | Oct. 06 2023 | 1 |


**Authors**
Juan Villegas

##   Description
General standard operating procedure for the AJA Sputter tool. This SOP describes how to manually configure and control a sputter deposition; recipes can be designed to follow the same or more steps for an automatic operation. 
This tool can be used to deposit metallic and insulating films (i.e. Aluminum, Niobium, Tantalum, Al2O3) onto a substrate material such as Silicon by sputtering from up to **three** target materials. When depositing insulating 
or non ferro-magnetic films, targets must be installed in the RF target source.


Standard installed targets:
| Gun | Materials|  Manufacturer | Strike Power | Max. Power Density | Deposition Power / Rate |
|---|---|---|---|---|---|
|1 (DC)| Nibioum Target  | AJA | 10 | 15.6 W/cm^2 | 400 W / 0.69 nm/s (Jan 2nd 2024) 
|2 (RF)| Aluminum Target  | AJA | 35 | 7.8 W/cm^2 | 200 W / 0.4 nm/s (Dec. 1st 2023)
|3 (DC)| Tantalum Target  | AJA | 30 | 23.2 W/cm^2 | 100 W / #.## nm/s
(The target openning in the standard guns is 57 mm in diameter)

##   Hazards
### Chemical Hazards:
|Chemicals|**Hazard Statements**|Safety Sign|
|---|---|---|
|  |  |  |

### Physical Hazards:
Heated substrates and parts can be extremely hot and cause severe burns, handle them with care. Intense light will be emitted from the plasma, avoid looking at it directly. 

### Equipment and Engineering Controls:
> Cleanroom standard PPE is sufficent. Use a thermometer or thermal camera to test when the substrate mount and load lock reaches room temperature. 
> Always close the viewport shutter when making a run to protect your eyes and prevent deposition on the viewport window, wear UV protecting glasses when inspecting the plasma.

|Personal Protective Equipment |
|---|
| Clenaroom gown. Latex or nitrile gloves.|

### Response Procedures
**Burns**: 
In case of burns, apply abundant water in the shower outside of the cleanroom and inform a safety officer, prefer to avoid using DI water direclty on the wound. For severe burns, avoid covering the injured area and request immediate assistance to be guided to an emergency attention area. Do not attempt to remove clothing or sticked nitrile (or latex) gloves.

**List emergency contact numbers**
- Lab in charge: Boulos Alfakes 052 722 6672
- **Civil Defense: 999**

## Handling, Storage and Waste Disposal of Hazardous Materials
Not applicable.

## Detailed Fabrication Procedure
### Overview
In the sputtering process, gas ions (typically Argon) are created in a plasma and accelerated into a target material. The impacting ions cause material to be removed (“sputtered”) 
from the target and deposited on a substrate in the vicinity of the target. To enable ignition of the plasma, the gas pressure is typically maintained in the range of 30-50 mtorr. 
In DC-sputtering a negative target potential is applied to accelerate the positively charged ions to the target. The impacting ions also create energetic secondary electrons that 
cause further ionization of the gas and a ring of magnets is placed below the target to trap and circulate the secondary electrons to further ignite the plasma. This is process is 
referred to as magnetron sputtering. All three sputter guns in the QFoundry use magnetron sputtering to increase the gas ionization rate and, hence, the deposition rate. DC-sputtering is limited 
to conducting materials like metals and doped semiconductors. For insulating materials, a radio frequency AC-voltage is applied to the target to prevent the charge buildup associated
with DC-magnetron sputtering. This technique is called RF-magnetron sputtering. Gun number **2** is an RF-magnetron source. 

In addition to Argon, Nitrogen and Oxygen are available 
for use in reactive ion sputtering applications. In reactive sputtering a reactive gas chemically combines with the target material. The substrate holder can be heated up to 850 C to 
enhance chemical reactions and allow for the deposited film to sustain different layer formation processes. The capability to apply RF-power to the substrate holder is also available, to sputter clean 
samples before deposition or further improve chemical reactions prior to depodition. 

<p align="center">
<img src ='https://github.com/tii-qfoundry/SOP/assets/14344419/bd80a577-b269-4fc4-961e-c6c7a5d3e2b8' width=600>
</p>

### System Checks
- Check thart the system water flow interlock light located on the top panel is ON (all LEDs in the chill water flow controller on the backside oif the mainframe should be ON).
- Check that all power supplies, vaccum sensors and pump controllers and the thickness monitor are ON.
- Check that the manual vent valve in the deposition chamber is CLOSED. Check that the nitrogen intake valve to the system's pumps is OPEN.
- In normal coinditions, both the load-lock and the deposition chamber should be in vaccum.

### Load a substrate
#### Step 1: Load the sample in substrate holder
1. Check that the nitrogen supply is ON, close the loadlock gate valve (3) and turn off the load-lock scrall-pump by switching the 'pump-off' button ont the pump's panel.
<p align="center">
<img src ='https://github.com/tii-qfoundry/SOP/assets/151726982/378e70e7-e613-4e27-b208-061cec6855d7' width=300>
</p>
2. Now turn off the turbo pumpo by switching the pump and motor buttons in the pfeiffer control panel. This will ramp down the turbo pump and start the venting procedure. Wait for the small turbo pump to reach a full stop and then the chamber to be at atmospheric pressure. Then open the load lock cover (5) and remove the subtsrate holder (chuck) after checking that it is at room temperature.
<p align="center">
<img src ='https://github.com/tii-qfoundry/SOP/assets/151726982/8f28af1e-3aff-4a62-a0ba-ca22bb189ee5' width=300>
</p>

> [!NOTE]
> Do not switch the breaker of the load-lock pumps to open the loadlock, nitrogen will keep flowing uninterruptedly if you do so. If the chamber doesn't fully vent after the turbo pump stops, check that the scroll is off and turn on and off the turbo to restart the vent cycle.

4. Mount your sample on the substrate holder using any of the screw points or using capton tape. Prefer to use a wafer as a backing material to avoid deposition on the substrate holder.
5. Install the chuck sample side down into the load-lock, ensuring that the one of the radial lines is aligned with the principal axis of the load lock (pointing left), and that no washers or screws are obstructing the interface with the transfer stage. Close the load-lock's lid cover (5).
6. Place the load lock lid back on and turn the 'Load Lock – Vacuum Pumps' switch the ON position. If the load-lock does not reach base pressure, vent the chamber and clean the lid and the o-ring with IPA.
7. When base pressure is reached (1e-6 tor), manually open the gate valve loosening the safety screw and rotating the handle anti-clock wise.
8. Check that the holding rod is in the upper position, or move it upards by turning antclock wise the holding rod handle.
9. Slowly slide the transfer arm to the left until clamp position is met by rotating the load-lock trasnfer rod handle (6).
10. Ensure top substrate holder angle monitor (1) is aligned to the left mark on the rotation knob (marked as 'unlocked' position). Then slowly move down the holding rod while checking its position through one of the viewports of the chamber. The key at the tip of the holding rod should slide into the central holes in the chuck and slighlty bend the tranbsfer rod assembly when in place.
11. Manually rotate the holding rod from the angle monitor (1) to the 'lock' position and move up the substrate holder assemply until the transfer rod is cleared.
12. Move the transfer rod back into the load lock and close the load lock vaccum gate valve.
    
### Deposition 
#### Step 1: Start the plasma (strike)
13. Set working distance. This is typically 30 and can be checked for each target.
14. Optionally turn rotation ON (this is necessary if you want to heat up the substrate).
15. In the GAS 1 area, ensure that Argon’s STPT (Set-Point) is set to 30sccm and trun on the gas.
16. In the PRESSURE CONTROL area, set the control pressure to 30 psi.
17. Activate the appropiate target gun, check the corresponding power supplies are on (in the mainframe) and set the strike power. Turn on the plasma.
18. Using the viewport check that the plasma is on and in the main panel that there is an appropiate voltage feedback (when the plasma is on should be similar to the input power value in Watts).
>[!NOTE]
>Sometimes the target has a hard time striking, there can be many reasons that this is the case. One common method to help the target strike is to open the shutter (click the large, dark green button) 
while the target is trying to strike. If this doesn’t work, increase the Ar gas flow but avoid increasing the striking power.

#### Step 2: Ramp up gun to the deposition voltage
19. Identify the process power for your target. Targets should be ramped at a rate of 1W/s and never exceed the specified power.
20. Enter the ramp time in the box next to the RAMP (sec) label.
21. Next, enter the process power where the strike power was, end hit enter on the keyboard. The ramp time will start counting down.
22. Once the ramp time has reached zero and the target is at process power, change the PRESSURE to 3 psi.

You can check the deposition rate using the thickness monitor:

23. Move the thickness mointor/shutter arm to the central position.
24. Set the thickness monitor to the correct film (Press the program menu and use the scroll wheel to find the desired film, then pess the scroll wheel to select it, and 
press the Program button again to exit).
25. Open the target shutter by pressing the large green button and press the Zero button on the thickness monitor.
26. Close the target shutter first and then move the shutter arm away form the central position once the rate of deposition has been determined.

#### Step 3: Deposit your film
The Sputtering tool has no deposition thickness control, so the film thickness is fully determined by the time the shutter is on.

27. Open the target shutter.
28. When the deposition time is completed, close the shutter.

#### Step 3: Ramp source gun down and turn off gun

29. Set the power rate of the target power supply to ensure a 1 W/s ramp and set the power to the baseline (~20 W).
30. When the base power is reached, set the power to 0 W and after a few seconds turn off the gun.
31. Turn off the gas supplies, sturn off ther the heater and stop the substrate rotation.
32. If you need a slow cool down of the substrate, leave it to do so in the process chamber, otherwise prepare for unloading the substrate by moving the holding rod up.

### Unload substrate

33. Follow the same steps from **Step 1** - item 5 to 10, but putting the angle position in the **'lock'** position first, and the in **'unlock'** once the substrate holder is on the trasnfer rod.
34. Confirm that the vaccum gate valve is closed and then vent the load-lock by turning off the breaker switch in the control panel.
35. After reaching atmospheric pressure, you can maunally shut the nitrogen gas supply while the sample is cooling down.
35. Unload the chuck and remove your sample, amking sure to remove any remaining caption tape. Load the chuck back into the load lock and close its lid, confirm that the nitriogen is on and pump down the load-lock. 

## Troubleshooting
- The VAT Vacuum Control Gate valve between the deposition chamber and the turbo pump should be fully open whenever the pump is turned on or when is shutdown to ensure proper equalization of the pressure between the two sides of the turbo. Do not try to open this gate valve when there is a pressure differential in the pump. To equalize in vaccum, let the turbo pump stop by itself and then manually vent the chamber using the auxiliary vent valve. Open the VAT gate valve once atmospheric pressure is reached.
- When a target gun runs at its maximum voltage (open circuit) or current (short circuit) the process will not run, even when there is a plasma being generated. Typically either condition indicates contamination or misplacemennt of the target in the source gun. Open the deposition chamber and clean carefully the target and the gun assembly using clean wipes and IPA, and after reassembling, confirm that there is no electrical continuity between the target and the outer shell of the assembly (for metallic targets). Running oxygen plasma at high $O_2$ concentrations can oxdize the target leading to the need of cleaning its surface.
