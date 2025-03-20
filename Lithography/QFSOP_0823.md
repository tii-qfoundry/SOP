# Electron Beam Lithography 
> [!NOTE]
> Add a note if necessary

> [!WARNING]
> Add a warning if necessary

<img src="https://github.com/user-attachments/assets/97d96ca0-3e70-40f6-bd11-82833db53eb3" alt="GHS-environment_hazard" width="10%">
<img src="https://github.com/user-attachments/assets/94b82d0d-5c50-405f-a46f-ece8cd7768e2" alt="GHS-Serious_health_hazard" width="10%">
<img src="https://github.com/user-attachments/assets/3550fb0c-dcdd-401a-b50f-7b3902fbf825" alt="GHS-health_atmospheric_hazard" width="10%">
<img src="https://github.com/user-attachments/assets/21d433f6-3f57-4625-8ebf-86a4338983a9" alt="GHS-toxic" width="10%">
<img src="https://github.com/user-attachments/assets/983e6245-662e-4cd8-993e-442595e19103" alt="GHS-corrosive" width="10%">
<img src="https://github.com/user-attachments/assets/38711323-85cc-411f-8bf3-b7e533037f9e" alt="GHS-compressed_air" width="10%">
<img src="https://github.com/user-attachments/assets/310c23a4-d01a-40c9-8cc4-763e5bc54e1e" alt="GHS-oxidizing" width="10%">
<img src="https://github.com/user-attachments/assets/da8b2d22-0196-42b6-a224-ba432b199e7f" alt="GHS-flamme" width="10%">
<img src="https://github.com/user-attachments/assets/44b80cd8-066f-43fc-b715-8cc2f4935edf" alt="GHS-explosive" width="10%">


| Reference | Publication Date | Revision |
|----|----|----|
|QFSOP_0325 | March 12 2025 | 0 |
(Reference all released previous versions of this document)
**Authors**


##   Description


Equipment: (List all equipment used).
| Item |  Equipment | Description | Manufacturer | Manual |
|---|---|---|---|---|
|1 | EBeam Lithography System   | | Raith | |
|2 | Hot Plate   | | | |
|3 | Acid Fume hood   | | | |
|4 | Solvent Fume hood   | | | |
|5 | Spin Coater   | | | |
|6 | Sonicator   | | | |
|7 | Hot Plate   | | | |

Materials: (List all consumables).
| Item |  Materials | Description | Manufacturer | MSDS |
|---|---|---|---|---|
|1 | Acetone    | CAS: 67-64-1 | | [MSDS](https://pubchem.ncbi.nlm.nih.gov/compound/180#datasheet=LCSS) |
|2 | Isopropanol   | CAS: 67-63-0 | | [MSDS](https://pubchem.ncbi.nlm.nih.gov/compound/3776#datasheet=LCSS) |
|3 | N-Methyl-2-pyrrolidone (NMP) | CAS: 872-50-4 | | [MSDS](https://pubchem.ncbi.nlm.nih.gov/compound/13387#datasheet=LCSS)|

 
##   Hazards
### Chemical Hazards:
|Chemicals|**Hazard Statements**| Safety Sign |
|---|---|---|
| Acetone | H225 (99.98%): Highly Flammable liquid and vapor, H319 (99.98%): Causes serious eye irritation, H336 (100%): May cause drowsiness or dizziness | <img src ="https://pubchem.ncbi.nlm.nih.gov/images/ghs/GHS02.svg" width=50> <img src ="https://pubchem.ncbi.nlm.nih.gov/images/ghs/GHS07.svg" width=50> |
| Isopropanol | H225 (99.98%): Highly Flammable liquid and vapor, H319 (99.98%): Causes serious eye irritation, H336 (100%): May cause drowsiness or dizziness | <img src ="https://pubchem.ncbi.nlm.nih.gov/images/ghs/GHS02.svg" width=50> <img src ="https://pubchem.ncbi.nlm.nih.gov/images/ghs/GHS07.svg" width=50> |
| NMP | H319 (99.98%): Causes serious eye irritation, H336 (100%): May cause drowsiness or dizziness H335 (100%): May cause respiratory irritation, H360 (97.78%): May damage fertility or the unborn child | <img src ="https://pubchem.ncbi.nlm.nih.gov/images/ghs/GHS08.svg" width=50> <img src ="https://pubchem.ncbi.nlm.nih.gov/images/ghs/GHS07.svg" width=50> <img width=300> |
|  | | <img src="https://github.com/user-attachments/assets/97d96ca0-3e70-40f6-bd11-82833db53eb3" alt="GHS-environment_hazard" width="10%"> <img src="https://github.com/user-attachments/assets/94b82d0d-5c50-405f-a46f-ece8cd7768e2" alt="GHS-Serious_health_hazard" width="10%"> <img src="https://github.com/user-attachments/assets/3550fb0c-dcdd-401a-b50f-7b3902fbf825" alt="GHS-health_atmospheric_hazard" width="10%"> <img src="https://github.com/user-attachments/assets/21d433f6-3f57-4625-8ebf-86a4338983a9" alt="GHS-toxic" width="10%">

### Physical Hazards:


### Administrative Controls:
Record of the aperture, dose and beam current used needs to be added to the ebeam log-book with record of the calculated beam speed and exposure time.
All the process needs to be carried inside the facilities of the quantum foundry, during working hours (8 am to 6pm).
User needs to be trained and authorized to use the equipment before excecuting this procedure.

### Equipment, Engineering Controls and Precaution:
- During ebeam-resist spin coating, a gas mask needs to be used.
- During ebeam-resist spin coating, the fume hood extraction needs to be set to level 2.

> [!WARNING]
> During high exhaust speed of fume hoods, the cleanroom is negatively pressurized (air will flow into the cleanroom from outside). The time the exhaust is kept at this coniditon needs to be minimized and particles count monitored after finishing. 


|Personal Protective Equipment |
|---|
| Clenaroom gown. Latex or nitrile gloves.|
| Gas mask. |

### Response Procedures
**First Aid**: 

**Spill Response**:

**Fire Response**:


**List emergency contact numbers**
- Lab in charge: Boulos Alfakes 052 722 6672
- **Civil Defense: 999**

## Handling, Storage and Waste Disposal of Hazardous Materials
### Storage


### Waste management


## Detailed Fabrication Procedure
### Overview
Lithography with electron beams consist in three main steps that need to be carefully monitored:
1. Resist deposition
2. EBeam exposure
3. Resist development.

### System Checks
Ensure that the Nitrogenm supply is open for both fumehoods, that the vaccum pump and nitrogen supply of the spin-coater are on and that compressed air and power is available for all used equipment. Check the status of the waste disposal containers 

### Procedure
#### Step 1: Substrate Preparation
1. 
2. 
3. 

#### Step 2: Cut the substrate and clean
4. 
5. 
6. 

## Troubleshooting
