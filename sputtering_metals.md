# Masked optical litography (395 nm)
> [!NOTE]
> When the AJA Sputterer is turned off, Nitrogen needs to keep flowing until the vaccum turbo pumps have come to a full stop. Then the nitrogen lines need to be manually shut down. Nitrogen must be kept open as long as the vaccum pumps are in use.

> > [!WARNING]
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

|Materials| Description | Manufacturer | Maximum Power Density | Rate Monitor Index |
|---|---|---|---|---|
|Nibioum Target  | |  | 15.6 W/cm^2 |1|
|Tantalum Target  | |  | 23.2 W/cm^2 |3|
|Aluminum Target  | |  | 7.8 W/cm^2 |2|

##   Hazards
### Chemical Hazards:
|Chemicals|**Hazard Statements**|Safety Sign|
|---|---|---|
|  |  |  |

### Physical Hazards:
Heated substrates and parts can be extremely hot and cause severe burns, handle them with care. Intense light will be emitted from the plasma. 

### Equipment and Engineering Controls:
> Cleanroom standard PPE is sufficent. Use a thermometer or thermal camera to test when the substrate, substrate mount and load lock reaches room temperature. 
> Always close the viewport shutter when making a run to protect your eyes and prevent deposition on the viewport window, wear UV protecting glasses when inspecting the plasma.

|Personal Protective Equipment |
|---|
| Clenaroom gown. Latex or nitrile gloves.|

### Response Procedures
**Burns**: 
In case of burns, apply abundant water in the shower outside of the cleanroom and inform a safety officer. For sever burns, avoid covering the injured area and request immediate assistance to be guided to an emergency attention area. Do not attempt to remove clothing or sticked nitrile (latex) gloves.

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
Close the gate vaccum valve (3) and turn off the load-lock pump by switching the corresponding vaccum pump breaker in the control panel, this will shut down the turbo piump and start the venting procedure. Wait for the small turbo pump to reach a full stop and 
then the chamber to be at atmospheric pressure. Then open the load lock cover (5) and remove the subtsrate holder. Mount your sample on the substrate holder using any of the screw points. 

#### 
![image](https://github.com/tii-qfoundry/SOP/assets/14344419/b8d964f6-6be2-4d93-a6a1-24220a25698c)

### Deposition: 
#### Step 1: Start the plasma (strike)

#### Step 2: Ramp up gun to the deposition voltage

#### Step 3: Deposit your film

#### Step 3: Ramp source gun down to rest voltage

#### Step 4: Ramp source gun down and shut down

### Unload substrate

