# 🚦 Railway Crossing Gate System  

This project demonstrates the use of the **Engineering Method** to design and implement a simple, reliable, and safe **railway crossing gate system**.  

The system automatically lowers gates, activates lights and alarms when a train or vehicle is detected, and only raises gates once the tracks are confirmed clear.  
The workflow follows a structured 7-step engineering design process.  

---

## 📂 Project Structure  

Each step of the project has its own folder and documentation:  

1. [Step 1 – Problem Analysis](Step1_ProblemAnalysis/ProblemAnalysis.md)  
2. [Step 2 – Exploring Alternatives](Step2_Alternatives/Alternatives.md)  
3. [Steps 3 & 4 – Evaluation & Decision](Step3-4_Evaluation/Evaluation.md)  
4. [Steps 5 & 6 – Planning & Implementation](Step5-6_Implementation/Implementation.md)  
   - [Flowchart](Step5-6_Implementation/railway_flowchart.png)  
5. [Step 7 – Testing & Refinement](Step7_Testing/Testing.md)  

---

## 🛠️ How It Works  

- **Inputs:**  
  - Train sensor (detects approaching trains)  
  - Vehicle sensor (detects vehicles on the track)  
  - Manual override switch (for emergencies)  

- **Outputs:**  
  - Gate actuator (raises/lowers gates)  
  - Warning lights (flashing when active)  
  - Alarm (audible warning for vehicles & pedestrians)  

- **Logic:**  
  - Gates lower if a train is approaching OR a vehicle is on the track.  
  - Gates raise only when the track is fully clear and a short delay has passed.  

---

## 👨‍💻 Collaboration  

- Tutor and lecturer added as collaborators.  
- Commit history maintained with clear messages (e.g., *“Added Step 5 algorithm”*, *“Uploaded flowchart”*).  

---

## 📊 Notes  

- Flowchart is saved as **PNG** inside the implementation folder.  
- Plain-English algorithm and test cases are included.  
- Refinements suggested for real-world reliability.  

---

✅ **Final Submission:** This GitHub repository serves as the complete documentation and implementation of the railway crossing gate system.  
