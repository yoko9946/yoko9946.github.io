---
title: "🚀 Solid Rocket Motor Modeling! Internal Ballistics"
draft: false
---
This project developed Python-based computational tools to model solid rocket motor ignition, burn dynamics, thermal loading, and structural performance. The work integrated thermochemistry from NASA CEA, internal ballistics, and heat transfer modeling to address both flight motor performance prediction and insulation test motor evaluation.

### **Technical Contributions:**

### **Motor Performance**
- Igniter Sizing & Thermal Modeling: Computed minimum igniter mass to achieve <50 ms ignition delay for ballistic test motors using thermal conduction equations, specific heat capacity, and target ignition surface temperature
- Burn Profile Classification: Classified motor pressure trace type (progressive, regressive, neutral, etc.) from experimental data trends
- Burn Rate vs. Pressure Calibration: Processed 9 static firing datasets of pressure–time traces, calculated rate-averaged pressure, and performed log–log regression to determine propellant burning rate parameters (a, n)
- Grain Geometry & Nozzle Design: Designed propellant grain geometry and nozzle throat size to meet specified thrust requirements across multiple flight phases (Ignition, Max-Q, Sustain, Tailoff)
- Simulation & Performance Validation: Modeled thrust and head-end pressure vs. time to verify compliance with customer specifications; established allowable burning rate tolerances to ensure thrust envelope is met

### **Thermal & Structural Analysis of Insulation Test Motor**
- Internal Ballistics Simulation: Developed and applied custom ballistics code to calculate time-resolved pressures, gas velocities, and mass fluxes at multiple motor stations for an insulation test section.
- Structural Analysis: Determined case and dome wall thickness requirements using yield strength safety factor criteria; computed total case and dome mass
- Thermal Protection System Design: Identified critical insulation zones outside the test section, selected insulation materials, and provided justification based on thermal loads and fabrication considerations
- Nozzle Heat Transfer Modeling: Applied alternate Bartz equation to compute static temperature, wall recovery temperature, heat transfer coefficient, and heat flux distribution along nozzle cone at peak operating pressure
- CEA Data Integration: Incorporated NASA CEA output into performance and heat transfer models to obtain thermophysical properties and expansion characteristics for AP/Al/HTPB propellant


