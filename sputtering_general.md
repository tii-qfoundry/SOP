# Magnetron Sputtering with DC and RF sources.
> [!NOTE]
> When the AJA Sputterer is turned off, Nitrogen needs to keep flowing until the vaccum turbo pumps have come to a full stop. Then the nitrogen lines need to be manually shut down. Nitrogen must be kept open as long as the vaccum pumps are in use.

> [!WARNING]
> When the substrate holder is heated, it needs to cool down in the vented load-lock chamber until it reaches a temperature below 50C (approximately 30 min) before any additional process is carried.

| Reference | Publication Date | Revision |
|----|----|----|
|QFR0323 | Oct. 06 2023 | 0 |


**Authors**
Juan Villegas

##   Description
General standard operating procedure for the AJA Sputter tool. This SOP describes how to manually configure and control a sputter deposition; recipes can be designed to follow the same or more steps for an automatic operation. 
This tool can be used to deposit metallic and insulating films (i.e. Aluminum, Niobium, Tantalum, Al2O3) onto a substrate material such as Silicon by sputtering from up to **three** target materials. When depositing insulating 
or non ferro-magnetic films, targets must be installed in the RF target source.


Standard installed targets:
| Gun | Materials|  Manufacturer | Strike Power | Maximum Power Density | Rate Monitor Index |
|---|---|---|---|---|---|
|1 (DC)|Nibioum Target  | | 30 | 15.6 W/cm^2 |1|
|2 (RF)|Aluminum Target  | | 35 | 7.8 W/cm^2 |2|
|3 (DC)| Tantalum Target  | | 30 | 23.2 W/cm^2 |3|


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


## Detailed Fabrication Procedure
### Overview
In the sputtering process, gas ions (typically Argon) are created in a plasma and accelerated into a target material. The impacting ions cause material to be removed (“sputtered”) 
from the target and deposited on a substrate in the vicinity of the target. To enable ignition of the plasma, the gas pressure is typically maintained in the range of 30-50 mtorr. 
In DC-sputtering a negative target potential is applied to accelerate the positively charged ions to the target. The impacting ions also create energetic secondary electrons that 
cause further ionization of the gas and a ring of magnets is placed below the target to trap and circulate the secondary electrons to further ignite the plasma. This is process is 
referred to as magnetron sputtering. All three sputter guns in the QFoundry use magnetron sputtering to increase the gas ionization rate and, hence, the deposition rate. DC-sputtering is limited 
to conducting materials like metals and doped semiconductors. For insulating materials, a radio frequency AC-voltage is applied to the target to prevent the charge buildup associated
with DC-magnetron sputtering. This technique is called RF-magnetron sputtering. Gun number **2** is an RF-magnetron source. In addition to Argon, Nitrogen and Oxygen are available 
for use in reactive ion sputtering applications. In reactive sputtering a reactive gas chemically combines with the target material. The substrate holder can be heated up to 850 C to 
enhance chemical reactions and allow for the deposited film to sustaing different layer formation processes. The capability to apply RF-power to the substrate holder to sputter clean 
samples before deposition or further improve chemical reactions prior to depodition. 

<p align="center">
<img src ='https://github.com/tii-qfoundry/SOP/assets/14344419/bd80a577-b269-4fc4-961e-c6c7a5d3e2b8' width=600>
</p>

### Load substrate
#### Step 1: Load the sample in substrate holder
- Check that the nitrogen supply is ON, close the loadlock gate valve (3) and turn off the load-lock pump by switching the corresponding vaccum pump breaker in the control panel. This will shut down the turbo pump and start the venting procedure. Wait for the small turbo pump to reach a full stop and then the chamber to be at atmospheric pressure. Then open the load lock cover (5) and remove the subtsrate holder (chuck) after checking that it is at room temperature.
- Mount your sample on the substrate holder using any of the screw points or using capton tape. Prefer to use a wafer as a backing material to avoid deposition on the substrate holder.
- Install the chuck sample side down into the load-lock, ensuring that the one of the radial lines is aligned with the principal axis of the load lock (pointing left), and that no washers or screws are obstructing the interface with the transfer stage. Close the load-lock's lid cover (5).
- Place the load lock lid back on and turn the 'Load Lock – Vacuum Pumps' switch the ON position. If the load-lock does not reach base pressure, vent the chamber and clean the lid and the o-ring with IPA.
- When base ressure is reached (1e-6 tor), manually open the gate valve loosening the safety screw and rotating the handle anti-clock wise.
- Check that the holding rod is in the upper position, or move it upards by turning antclock wise the holding rod handle.
- Slowly slide the transfer arm to the left until clamp position is met by rotating the load-lock trasnfer rod handle (6).
- Ensure top substrate holder angle monitor (1) is aligned to the left mark on the rotation knob (marked as 'unlocked' position). Then slowly move down the holding rod while checking its position through one of the viewports of the chamber. The key at the tip of the holding rod should slide into the central holes in the chuck and slighlty bend the tranbsfer rod assembly when in place.
- Manually rotate the holding rod from the angle monitor (1) to the 'lock' position and move up the substrate holder assemply until the transfer rod is cleared.
- Move the transfer rod back into the load lock and close the load lock vaccum gate valve. 

<p align="center">
<img src ='https://github.com/tii-qfoundry/SOP/assets/14344419/b8d964f6-6be2-4d93-a6a1-24220a25698c' width=400>
</p>

### Deposition ###
#### Step 1: Start the plasma (strike)
- Set working distance. This is typically 30 and can be checked for each target.
- Optionally turn rotation ON (this is necessary if you want to heat up the substrate).
- In the GAS 1 area, ensure that Argon’s STPT (Set-Point) is set to 30sccm and trun on the gas.
- In the PRESSURE CONTROL area, set the control pressure to 30 psi.
- Activate the appropiate target gun, check the corresponding power supplies are on (in the mainframe) and set the strike power. Turn on the plasma.
- Using the viewport check that the plasma is on and in the main panel that there is an appriate voltage feedback (when the plasma is on should be similar to the input power value in Watts).
>[!NOTE]
>Note, sometimes the target has a hard time striking, there can be many reasons that this is the case. One common method to help the target strike is to open the shutter (click the large, dark green button) 
while the target is trying to strike. If this doesn’t work, increase the Ar gas flow but avoid increasing the striking power.

h. Identify the process power for your target. The general rule is that targets can be ramped at a rate of 1W/s. To 
calculate the necessary ramp time, simply subtract the strike power from the process power.
i. First, enter the ramp time in the box next to the RAMP (sec) label.
j. Next, enter the process power where the strike power was, end hit enter on the keyboard. The process power will 
grey out and the ramp time will start counting down.
k. Once the ramp time has reached zero and the target is at process power, change the PRESSURE to 3.
l. If using the thickness monitor, ensure that it is set to the correct film. To change the film, press the Program
menu and use the scroll wheel to find the desired film. Once on the film, press the scroll wheel to select it, and 
press the Program button again to exit.
m. It is important to do the following two steps at the same time. Open the shutter by pressing the large green button 
and press the Zero button on the thickness monitor.
n. Ensure the shutter has fully opened by looking in to the view port. If the target plasma is visible the shutter has 
opened properly. Close the view port shutter.
o. Once the process time or film thickness has been reached, close the shutter by pressing the now big bright green 
button.
p. Change PRESSURE to 30.
q. First, enter in the same ramp time as calculated in step h.
r. Next, enter the strike power and hit enter on the keyboard.
s. Once the ramp time has reached zero, turn off plasma by pressing the green ON button below the pink circle.
t. Click OPEN in the PRESSURE CONTROLLER section. Turn GAS 1 off by clicking the green ON button. Turn 
ROTATION off by clicking the green ON button.
u. Move to step 4. and remove sample
#### Step 2: Ramp up gun to the deposition voltage

#### Step 3: Deposit your film

#### Step 3: Ramp source gun down to rest voltage

#### Step 4: Ramp source gun down and shut down

### Unload substrate

