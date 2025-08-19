# Steps 5 & 6 – Planning and Implementation  

## Plain-English Algorithm  

1. **Start system** and initialise all sensors.  
2. **Continuously check inputs** (train sensor + vehicle sensor).  
3. If **train approaching = true OR vehicle on tracks = true** →  
   - Lower gates  
   - Activate warning lights and alarms  
4. Keep gates **lowered until the train has passed**.  
5. Once **no train is approaching**, check vehicle sensor:  
   - If tracks are clear → wait **3 seconds**, then raise gates and deactivate alarms.  
   - If vehicle is still present → keep gates lowered until clear.  
6. **Manual override switch**: railway staff can operate gates in emergencies, but gates only raise if sensors confirm it is safe.  
7. **Repeat process continuously**.  

---

## Flowchart  

The process is represented visually in the flowchart below:  

![Flowchart](Step5-6_Implementation/railway_flowchart.png)
