# Cleanmroom Shutdown Routine.
> [!NOTE]
> The Cleanroom should in general not be shutdown unless systems will be out of operation for over a month or maitenance schedules requires so. Equipment will always change their operational conditions after a shutdown and fabrication recipes need to be tuned accordingly. Some equipment components will have their lifetime reduced when subject to shutdowns.

> [!WARNING]
> Turbo pumps need to come to full stop before vent lines are closed to avoid them staying at mechanical resonance points for long time.

| Reference | Publication Date | Revision |
|----|----|----|
|QFR0423 | Oct. 17 2023 | 0 |
|QFSOP_0523 | Oct. 17 2023 | 1 |


**Authors**
Juan Villegas

##   Description
General standard operating procedure to prepoare the cleanroom for a general shutdown.

##   Hazards
### Chemical Hazards:
|Chemicals|**Hazard Statements**|Safety Sign|
|---|---|---|
|  |  |  |

### Physical Hazards:
Heated substrates and parts can be extremely hot and cause severe burns, handle them with care. Intense light will be emitted from the plasma, avoid looking at it directly. 

### Equipment and Engineering Controls:
> Cleanroom standard PPE is sufficent.

|Personal Protective Equipment |
|---|
| Clenaroom gown. Latex or nitrile gloves.|

### Response Procedures

**List emergency contact numbers**
- Lab in charge: Boulos Alfakes 052 722 6672
- **Civil Defense: 999**

## Handling, Storage and Waste Disposal of Hazardous Materials
Not applicable.

## Detailed Fabrication Procedure
### Overview
Each system in the cleanroom needs to follow proper shutdown to ensure that the lifetime of its components is maximized and that their operational conditions are minimally chnaged. 
In general it comprises of shutting off process gas flows, electron beam sources, vaccum pumps, purge gases and compressed air, electrical power supplies for each equipment in that order, and the general exhaust systems, air handling units and main power supplies. 
Emergency systems and controls and access controls should remain active or replaced for temporary controls while shutdown.
This SOP describes the shutdown procedures for each individual system.

### RAITH EBeam Litography System
#### Shutdown of Column and Computers.
- Set *Column Stop* mode in the RAITH software suite, and wait for the column to shut down.
- Close all windows and exit the software.
- Turn off the computer from windows.
- 
#### System Shutdown
- Press the *Standby* button in the ebeam body and wait for 2 minutes.
- Press the *off* button.
- Close the compressed air, water and nitrogen lines.
- Go to the main power switch (outside of the cleanroom, on top of the power distribution cabinet) and set the switch to the *OFF* position. All units in the rack should now be disconnected from the supply.

### AJA Sputtering System
#### Stop all sources
- In the control software, make sure to ramp down any gun that is active and close all shutters.
- Turn off the power switch in each of the RF and DC sources.
- Turn off the power to the heater stage.

#### Stop Pumping
- Turn off the load-lock roughing pump and stop the turbo pump of the load-lock from its control panel.
- Switch off the power bracket to the main chamber pumps.
- Wait for the loadlock turbo to get to a complete stop and open the breaker to that sup[plies the loadlock pumps.
- Close the nitrogen valve that supplies the system vents.

#### Shutting the system
- Close the manual shutter and attach a cable tie to keep it in the closed position.
- Close the control software and shutdown the computer
- Turn off all remaining power supplies.
- Close all remaining gas supply valves and chilled water intake.


## Troubleshooting

