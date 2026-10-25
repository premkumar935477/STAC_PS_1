🚀 Operation Ember Ascent — OpenRocket Extraterrestrial Flight Design Challenge

STAC WARS | PS1 | Mustafar Mission

«May the Code Be With You.»

🌌 Project Overview

Operation Ember Ascent is an extraterrestrial rocket flight-design challenge that involves designing, simulating, and optimizing a two-stage sounding rocket using OpenRocket for a mission on Mustafar, a fictional planet with extreme atmospheric conditions.

The objective is to deliver a 1 kg scientific payload to an apogee of 4,000 metres, deploy the payload and recovery systems at apogee, and safely recover both the payload and rocket.

Unlike a conventional Earth-based rocket design, this mission requires a customized planetary environment and careful analysis of propulsion, aerodynamic stability, flight performance, and parachute recovery.

🎯 Mission Objectives

- Design a complete two-stage sounding rocket in OpenRocket.
- Configure the simulation environment using Mustafar's planetary parameters.
- Reach an apogee of 4,000 ± 100 m.
- Carry a scientific payload of 1.00 ± 0.05 kg.
- Keep the rocket length within 2,200 mm.
- Keep the combined motor total impulse at or below 2,800 N·s.
- Deploy the drogue parachute, payload, and main parachute at the specified apogee.
- Achieve a descent velocity of 4–8 m/s.
- Analyze stability, maximum velocity, Mach number, descent rate, and drift.
- Compare flight performance under Mustafar and Earth atmospheric conditions.

🪐 Mustafar Environmental Parameters

The following conditions are specified in the mission brief.

Parameter| Mustafar Condition
Surface gravity| 6.50 m/s²
Surface pressure| 75 kPa
Surface temperature| 700 K
Atmospheric density| 0.374 kg/m³
Wind velocity| 10 m/s
Wind direction| 270° relative to launch direction
Launch-site altitude| 0 m

These parameters must be configured appropriately in the OpenRocket simulation.

📋 Mission Constraints

Requirement| Target
Apogee| 3,900–4,100 m
Payload mass| 0.95–1.05 kg
Rocket length| ≤ 2,200 mm
Combined motor total impulse| ≤ 2,800 N·s
Drogue deployment| At apogee
Payload deployment| At apogee (target 4,000 m)
Main parachute deployment| At apogee (target 4,000 m)
Descent velocity| 4–8 m/s
Recovery| Parachute recovery for payload and rocket

All applicable requirements must be satisfied simultaneously.

🧱 Rocket Design and Mass Constraints

The mission allows one of the following body materials:

Body material| Maximum total mass, including motor
Aluminium| 15 kg
Cardboard| 10 kg
PVC| 11.5 kg

The selected material must be stated in the final report. Motor mass must come from the selected motor definition in OpenRocket, and manual mass overrides on rocket components are not permitted.

The simulated stability characteristics must also be reported. The mission brief does not prescribe a numerical minimum stability margin.

🛠️ Tools and Technologies

- OpenRocket — rocket modeling, flight simulation, and design optimization.
- GitHub — version control, project documentation, and submission.
- CSV data analysis — examination of flight simulation outputs.
- PDF reporting — presentation of design methodology, results, and conclusions.

🔬 Simulation and Analysis Methodology

1. Environment Configuration

Configure the Mustafar launch environment using the specified gravity, pressure, temperature, atmospheric density, wind speed, and wind direction.

2. Rocket Modeling

Build the complete two-stage rocket, including its geometry, body material, payload, motors, and recovery systems.

3. Flight Simulation

Run OpenRocket simulations and examine apogee, maximum velocity, acceleration, stability margin, Mach number, and recovery performance.

4. Design Optimization

Iteratively refine the rocket design to satisfy the mission constraints together rather than maximizing altitude alone.

5. Earth–Mustafar Comparison

Run comparable simulations under Earth and Mustafar conditions. Where practical, change one environmental parameter at a time to investigate its effect on flight performance.

Investigate the following hypotheses:

- Lower gravity may reduce the rocket's weight and change its ascent and time to apogee.
- Lower atmospheric density may reduce aerodynamic drag and change parachute descent rates.
- Extreme temperature may change the local speed of sound and the calculated Mach number.
- Crosswind may influence weathercocking, trajectory, and landing drift.
- Atmospheric changes may affect aerodynamic stability throughout flight.

The final report should compare simulated results with these hypotheses rather than assume that each effect will occur in a particular magnitude.

📊 Results and Performance Evaluation

Record the actual OpenRocket simulation results in this section after testing the final design.

Metric| Mission target| Simulated result
Apogee| 3,900–4,100 m| To be measured
Payload mass| 0.95–1.05 kg| To be measured
Rocket length| ≤ 2,200 mm| To be measured
Total motor impulse| ≤ 2,800 N·s| To be measured
Maximum velocity| Report result| To be measured
Stability margin| Report result| To be measured
Mach number| Report result| To be measured
Descent velocity| 4–8 m/s| To be measured
Landing drift| Report result| To be measured

Note: Results will be updated after simulation and validation. No performance values are claimed until verified in OpenRocket.

📁 Repository Structure

The repository will contain the required mission deliverables:

- "TeamName_Rocket.ork" — complete, editable OpenRocket design and Mustafar simulation.
- "TeamName_FlightData.csv" — flight data exported from OpenRocket.
- "TeamName_Report.pdf" — design approach, environmental configuration, recovery system, simulation results, and Earth–Mustafar comparison.
- "assets/rocket_design.png" — optional rocket-design screenshot.

Replace "TeamName" with your actual team name in the filenames and repository structure.

📦 Final Deliverables

The submission must include:

1. OpenRocket simulation file (".ork") containing the complete editable rocket design.
2. Flight simulation data (".csv") exported from OpenRocket.
3. Technical report (".pdf") documenting the design, launch conditions, recovery system, results, and environmental comparison.

Ensure the OpenRocket file contains all components and does not depend on missing components or external references.

👥 Team

Team Name: S^3PD

Team Members:

- Divya
- abhiraj

🏁 Mission Status

Current phase: Design and simulation.

The mission is complete only when the final rocket meets all applicable constraints, the simulation data has been evaluated, and the required deliverables are ready for submission.

---

Designed for the STAC WARS PS1 OpenRocket Extraterrestrial Flight Design Challenge.
