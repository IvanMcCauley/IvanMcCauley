# 👋 Hi, I’m Ivan McCauley  
### Mechatronic Engineering Graduate | Autonomous Driving & ADAS Systems

I build small-scale ADAS and autonomy projects to understand how systems behave in real scenarios, especially how perception outputs, decision logic, and safety margins interact.

My work is focused less on isolated algorithms and more on expected vs actual behaviour, failure modes, and why a system makes a particular decision near safety limits.

Since graduating, I’ve built projects around braking behaviour evaluation, perception → planning pipeline and BEV-based path planning, with a strong emphasis on system testing, validation, and behaviour analysis.

I’m currently seeking entry-level roles in ADAS / autonomous driving, particularly in systems engineering, system testing, or validation.

---

## 🔧 Technical Focus
- **Languages:** C++, Python, MATLAB  
- **Core Tools:** ROS 2, OpenCV, Simulink, Linux, Git  
- **Domains:** Autonomous Driving / ADAS, Decision Logic, Path Planning, Control Systems, Robotics  

---

## 🌱 Selected Work

### Independent (post-grad)

- 🛑 **End-to-End ROS 2 Braking Pipeline:** A staged braking system built to evaluate **system behaviour as scenario boundaries are pushed**, with KPI-based analysis near safety limits (chatter, margins, stability).
  - **Stage 1:** [C++17 Braking Decision Library](https://github.com/IvanMcCauley/braking_decision_lib): Implemented the core stopping-distance logic with parameterised braking rules, input validation, and unit-tested C++ APIs.
  - **Stage 2:** [ROS 2 Brake Decider Node](https://github.com/IvanMcCauley/ros2_brake_decider): Integrated the braking logic into a ROS 2 node with live inputs, configurable parameters, and real-time /brake_cmd outputs.
  - **Stage 3:** [ROS 2 Closed-Loop Validation Simulation](https://github.com/IvanMcCauley/ros2_brake_validation_sim): Built a 1D closed-loop simulator to replay brake commands through vehicle motion and verify that the system actually stops safely.
  - **Stage 4:** [System-level behaviour evaluation](https://github.com/IvanMcCauley/adas-braking-behaviour-evaluation): Built a scenario-based evaluation pipeline to compare expected vs actual closed-loop braking behaviour using KPIs, exposing instability and hidden failure modes


- 🧠 **[Dashcam BEV Path Planner](https://github.com/IvanMcCauley/Project_Dashcam-BEV-Path-Planner)**: Autonomous driving simulation using real dashcam footage, BEV projection, occupancy grid mapping, and behaviour-aware A* planning.


- 🧭 **[Autonomous Path Planning Simulator](https://github.com/IvanMcCauley/Project_Path-Planner-Simulation)**: Python-based decision-logic simulator with A* planning, LIDAR-style limited perception, frontier exploration, and dynamic replanning.


- 🛣️ **[Dashcam Lane Detection](https://github.com/IvanMcCauley/Project_Dashcam-Lane-Detection)**: OpenCV-based lane detection pipeline using ROI masking, Hough transform, and real-time lane overlay on dashcam video.



### Academic (selected)

- 🎛️ [Electric Power Steering (EPS) Control Analysis](https://github.com/IvanMcCauley/eps-control-analysis-matlab-simulink): 
System-level EPS modelling and closed-loop behaviour analysis in MATLAB/Simulink, evaluating PID control using time-domain KPIs and stability checks.
- 📌 [5-Second Stop Rig](https://github.com/IvanMcCauley/Project_5-Second-Stop-Rig) - Arduino-based reaction-time device  
- 🤖 [Autonomous Navigating Robot](https://github.com/IvanMcCauley/Project_Autonomous-Navigation-Robot) - Wi-Fi connected mobile robot  
- 🚗 [AGV - Autonomous Guided Vehicle](https://github.com/IvanMcCauley/Project_AGV-Autonomous-Guided-Vehicle) - line-following vehicle with optical sensing and MCU control

---

## 📫 Contact
- [LinkedIn](https://www.linkedin.com/in/ivan-mccauley-82b17a177)  
- [Email](mailto:mccauleyivan03@gmail.com)
