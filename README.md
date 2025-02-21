# Pellet Extruder
## 1. Project Overview
### 1.1 Project Name
> *Pellet extruder integration into Volterra*

### 1.2 Description
> *Install an outsourced pellet extruder into the Volterra 400 3D printer by integrating the electronics and optimizing mechatronics.*

### 1.3 Goals & Objectives
- *Installing the pellet extruder*
- *Autobed Levelling*
- *Mechatronics Restoration*
- Print usable samples through pellet extruder after installing it on volterra


### 1.4 Key Features
- *Outline the main functionalities and design goals.*
- Material pellets are used instead of filament.
- Reduced material cost.
---

## 2. Requirements
### 2.1 Hardware Requirements
- *List required components, specifications, and dependencies.*
- FOR EXTRUDER =>
- Nozzle
- Nozzle Heater
- Thermistor
- Stepper motors
- Feeder Screw
- Cooler Fans
- PTFE Casing
- Aluminium Casing
- Hopper
- Mounting Plate
- Fasteners
- Standoffs
- FOR CARRIAGE=>
- Aluminium carriage plate
- LM10uu Bearings
- Guide rods
- Racer chain
- Fasteners
### 2.2 Software & Tools
- *Mention any software, programming languages, or design tools needed.*
- Fusion 360 for extruder and assembly design
- Fracktory for slicing the 3D printing components

### 2.3 Constraints & Challenges
- *Document limitations such as cost, size, power consumption, etc.*
- Limited knowledge of electronics inside the printer
- Refurbishing the machine, removing old parts, and integrating old chassis with new design
- More noise and vibration during operation than traditional filament-based machines.
- Requires higher temperature to melt pellets.
- Hopper positioning and interference with bearing housing and guide rods.
- unavailability of Long screw 25mm standoffs, hence used Helicoil for fastening.
---

## 3. Development Log
*(Use this section to record ongoing research, issues, and progress. Clean it up as the project solidifies.)*
- Transferring electronics from another 3d printer to Volterra
- Mounting holes for extruder mount on the carriage
- Mounting holes for load cell
- CAD for hopper
- CAD for carriage assembly
- Electronics connections and firmaware installation on raspberry pi
- Testing extruder and motors

### 3.1 Research Links & Resources
| Date       | Link | Notes |
|------------|------|-------|
| YYYY-MM-DD | [Link](#) | *Brief note on relevance* |

### 3.2 Key Decisions & Changes
- decided to go with the previously designed carriage plate and mount PE using standoffs as the new design will hinder the X-axis movements.
- 

### 3.3 Issues & Solutions
- **Issue:** *Describe the problem.*
  - **Solution:** *Describe how it was solved.*

---

## 4. Development Process
### 4.1 Initial Steps
- *Outline the first actions taken to get started.*

### 4.2 Iterative Development
- *Document key development phases and their outcomes.*

### 4.3 Final Steps
- *Summarize the last steps taken before project completion.*

---

## 5. Testing & Validation
### 5.1 Test Cases
| Test | Expected Result | Actual Result | Status |
|------|----------------|---------------|--------|
| *Test Name* | *What should happen?* | *What actually happened?* | ✅ / ❌ |

### 5.2 Performance & Reliability
- *Describe stress tests, benchmarks, and overall performance analysis.*

---

## 6. Final Documentation & Learnings
### 6.1 Finalized Steps
- *Document the finalized workflow for future reference.*

### 6.2 Lessons Learned
- *What worked well? What could be improved?*

### 6.3 Next Steps
- *Outline future improvements or extensions to this project.*

---

## 7. Additional Notes
*(Any other important information.)*
