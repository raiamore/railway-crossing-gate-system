# Step 1: Exploring the Problem  

## Restating the Problem in Your Own Words  
The task is to create a simple, intuitive logic system that automatically manages gates at a railway level crossing.  
- The gates should lower to block road traffic whenever a train is nearing the crossing or if any vehicle remains on the tracks, **preventing collisions**.  
- They should only raise once the train has fully passed and the tracks are clear, ensuring safety without relying on manual operation.  

---

## Logic  
- **Lowers gates** when a train is approaching **OR** a vehicle is detected on the tracks.  
- **Raises gates** only when no train is approaching **AND** no vehicle is present.  

---

## Inputs and Outputs  

### Inputs  
| Input                | Description                                             |
|----------------------|---------------------------------------------------------|
| Train sensor         | Detects if a train is approaching within a safe distance. |
| Vehicle sensor       | Detects if a vehicle is present on the tracks.          |
| Manual override switch | Allows railway staff to control gates in emergencies. |

### Outputs  
| Output          | Description                                                |
|-----------------|------------------------------------------------------------|
| Gate actuator   | Raises or lowers gates.                                    |
| Warning lights  | Flash when gates are down or a train is approaching.       |
| Alarm sound     | Provides an audible warning to road users.                 |

---

## Context, Constraints, and Stakeholders  

### Context  
This system operates in **railway environments** where trains and road vehicles intersect, such as urban or rural crossings in Australia.  
It aims to reduce accidents, which are common at unguarded crossings, by **automating gate operations** based on real-time sensor data.  

### Constraints  
- **Technical:** Sensors must be weather resistant, accurate, and reliable in various conditions. They must function in real-time (<5s delay).  
- **Economic:** Keep costs low (under $10,000 per unit) and maintenance minimal by using off-the-shelf sensors and simple hardware to make it feasible for widespread use.  
- **Social:** Minimise traffic delays to avoid frustration for drivers and pedestrians; ensure the system is user-friendly for maintenance staff.  
- **Environmental:** Components should withstand harsh weather (rain, heat, dust in northern Australia). Use durable, low-power materials to reduce energy use.  
- **Legal/Ethical:** Must comply with AS 7502, the Australian Rail Safety National Law, and standards from the **Office of the National Rail Safety Regulator (ONRSR)**. Prioritise human safety and avoid false positives that could cause unnecessary disruptions.  

### Stakeholders  
- **Railway operators and maintenance teams** – need reliable, easy-to-fix systems.  
- **Motorists and pedestrians** – benefit from safer crossings but are affected by delays.  
- **Government regulators (ONRSR)** – ensure compliance and safety standards.  
- **Local communities** – impacted by noise or installation.  
- **Train drivers** – rely on clear signals for smooth and safe operations.  
