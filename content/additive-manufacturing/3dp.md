---
title: "DIY Mini CNC Laser Engraver"
date: 2024-12-16
draft: false
---

### Introduction
The objective of this project was to explore how additive manufacturing could enhance low-cost CNC systems by improving their functionality and accessibility. Through the use of 3D printed components, the work resulted in a stable and customizanle DIY CNC laser engraver.


---

### Primary Components

The DIY Mini CNC Laser Engraver integrates a range of electronic, mechanical, and 3D printed
components. Each part was selected for its functionality, accessibility and contribution to the overall system design. 
![DIY CNC Laser Engraver](/images/additive-manufacturing/pc.png)

---

### 3D Printing
All structural parts were fabricated using PLA on two printers:  
- **Bamboo Lab X1C** (phosphorescent PLA with glow-in-the-dark features)  
- **LuxStar LX-100** (white PLA for structural parts)  

![3D printed parts](/images/additive-manufacturing/3d.png)

A special thanks to the [USC Center for Advanced Manufacturing](https://sites.usc.edu/cam/)  
for providing valuable advices and access to equipment and support in printing the 3D parts.

---

### Assembly & Software
- Hardware assembly included precise alignment, soldering, and secure wiring. 

![Soldering](/images/additive-manufacturing/S1.png)

- Wiring Diagram

![Wiring Diagram](/images/additive-manufacturing/WD.png)

- Configured the engraver by combining Arduino IDE for firmware, GRBL for motion control, and LaserGRBL for G-code execution.

---

### Challenges & Insights

Throughout the build, I encountered several engineering challenges that became valuable learning experiences:
- **3D Printing Tolerances** — Some printed parts (e.g., sliders and base) required manual refinements to achieve smooth fits. This emphasized the importance of accounting for tolerance and precision in CAD design.  
- **Component Compatibility** — Initial stepper motors did not match the required dimensions. By sourcing properly sized replacements, I restored stability and ensured reliable motion control.  
- **Material Behavior** — Thermal contraction during printing introduced minor surface imperfections. This highlighted the need to optimize print settings and select materials with greater dimensional stability.  

Through these challenges, I learned the value of designing with precise tolerances, verifying component compatibility before fabrication, and staying flexible through iterative troubleshooting. These lessons strengthened my ability to approach additive manufacturing projects with accuracy, foresight, and adaptability.

---

### Results & Future Directions
- Successfully integrated hardware and electronics, demonstrating proof-of-concept.  
- Next steps: optimize GRBL configuration, scale up to a larger system with improved tolerances, modularity, and reliability.  
![Engraving test result](/images/additive-manufacturing/TR.png)
📄 [Download Full Report (PDF)](/files/AM_report.pdf)

---