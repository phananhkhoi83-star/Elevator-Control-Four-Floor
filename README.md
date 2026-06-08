# Four-Floor Elevator Control System 

##  Project Overview
This project simulates the control logic of a four-floor elevator system using a Siemens S7-1200 PLC. The system manages floor requests, door operations, and safe vertical movement between four distinct levels.

* **Inspiration:** The mechanical operation concept was inspired by "Ngọc Automation" on YouTube. The PLC control logic, I/O mapping, and priority algorithms were developed independently.

##  Control Logic
The system implements a priority-based control strategy:
* **Request Handling:** Captures calls from inside the cabin and external call buttons at all four floors.
* **Floor Logic:** Determines the direction of travel (up/down) based on current position and requested floors.
* **Safety Protocols:** Ensures doors are closed before elevator movement and monitors floor arrival limit sensors to stop precisely.
* **System Status:** Manages idle, moving, and door-opening states.

##  Tech Stack & Software
* **PLC Programming:** TIA Portal
* **Hardware Target:** Siemens SIMATIC S7-1200
---
###  Author
**Phan Anh Khôi**
Control and Automation Engineering Student at University of Transport Ho Chi Minh City
