# TASK 1 : Rules in the Rule Book Written by Blood
**Objective :** To explore the methodology behind air crash investigations and learn how aviation safety evolves from past incidents. \
**Task :**
- Write a detailed report of the air crash investigation, the report should include:
- Details of the flight, place, time, pilot details and an introductory paragraph about the accident which occurred /was about to occur including the losses occurred.
- Explain in brief about the aircraft.
- Using the Swiss Cheese Model analyze the key contributing factors (technical, human, environmental etc.) and also explain how each of these factors (layers of the Swiss Cheese) accelerated the accident when aligned together.
- State the various theories and assumptions which took place during the investigation and also mention the reasons which led to the elimination/confirmation of these theories.
- Reflect on what lessons were learned and how aviation standards changed post-accident.

**Report :** \
I have reported on crash of American Airlines flight 965, crashed on 20th december 1995. \
[click here](https://github.com/Vishalpolicepatil/Report-level-2/blob/52a7d67ffd8e6aa5e7c8e70c63757dfe294f611e/Cali%20Crash%20(2)%20(1).pdf) to view my detailed report. \
[click here](https://github.com/Vishalpolicepatil/Report-level-2/blob/52a7d67ffd8e6aa5e7c8e70c63757dfe294f611e/A96_90_106.pdf) to view the official investigation report conducted by National Transportation Safety Board.
# TASK 2 : Introduction to MATLAB 
**Objective :** \
To gain foundational knowledge of MATLAB and Simulink. \
**Task :** \
Complete the MATLAB Onramp course. \
Complete the Simulink Onramp course. \
Download and upload both certificates as proof of completion. \
**Outcomes&Learnings :** \
I have completed the MATLAB Onramp course in which i learned the fundamentals of the *MATLab* \
**MATLab Onramp Course :** \
**1. Navigate the MATLAB Desktop and Editor :** I have learned to use the interface and write my own scripts to save and run your code. \
**2. Work with Variables and Arrays:** I have learned to perform both element-wise and matrix operations, as well as use built-in functions. \
**3. Import and Visualize Data:** Practiced for bringing data into MATLAB from external files and creating plots to visualize it. \
**4. Program with MATLAB:** Got an introduction to basic programming concepts like logical arrays, conditional statements, and for loops to write more complex programs. \
**5. Use MATLAB Documentation:** I have learned how to find information and help within MATLAB's comprehensive documentation. \
**6. Complete a Final Project:** Analyzing light from a star to determine its motion. \
**Certificate :** \
![alt text](https://github.com/Vishalpolicepatil/Report-level-2/blob/main/Screenshot%202025-08-27%20180014.png?raw=true)

# TASK 3 : Autonomous Flight Planning & Execution

**Objective :** \
To understand and practice autonomous flight mission planning using Mission Planner and the ArduPilot simulator. \
**Task :** \
1.To learn about the Heads Up Display (HUD)available in the Mission Planner.  
### Software in the loop (SITL)
Software in the loop is a method of testing and validation of the code in the simulation environment. \
![image](https://raw.githubusercontent.com/Vishalpolicepatil/Report-level-2/refs/heads/main/lU9iQe6VrI7K1I7w7FjgFeAxtSU.avif) \
SIL has many features that make it advantageous for testing in the automotive industry:
- SIL simulations can be run on any standard desktop computer without requiring the special equipment or test benches needed for HIL testing.This makes it cost-effective to deploy SIL testing across many instances, which reduces testing bottlenecks and speeds up the development process.
- Because the simulation is being performed entirely in software, the testing can actually go faster than it would in real time.
- Simulation programs deliver flexibility and repeatability. Testers run multiple simulations, adjusting for a single variable while all other aspects of the scenario remain constant, creating a more effective feedback loop with software developers.
- SIL helps decouple software and hardware development, allowing software developers to create new features and functions at their own accelerated pace.
- Organizations can test pieces of code or components of a complex solution as they are being developed rather than waiting for the entire product to be finished.
- With multithreading, multiple tests can be conducted at the same time rather than sequentially, which also saves time and improves efficiency.
- The simulations developed for SIL can be reused on HIL tests to monitor physical hardware performance and cross-correlations.
- The results can be easily shared across development teams from technology providers, OEMs and third parties.

### Heads Up Display (HUD)
The Heads-Up Display (HUD) in Mission Planner is a critical component of the ground control station software, providing real-time flight data and situational awareness for operators of unmanned aerial vehicles (UAVs), rovers, and other robotic vehicles. \
![alt text](https://github.com/Vishalpolicepatil/Report-level-2/blob/main/Screenshot%202025-08-30%20150826.png?raw=true) \
1.Airspeed (Groundspeed if no airspeed sensor is fitted) \
2.Crosstrack error and turn rate (T) \
3.Heading direction \
4.Bank angle \
5.Telemetry connection link quality (averaged percentage of good packets) \
6.GPS time \
7.Altitude (Blue bar is the rate of climb) \
8.Airspeed \
9.Groundspeed \
10.Battery status \
11.Artificial Horizon \
12.Aircraft Attitude \
13.GPS Status \
14.Distance to Waypoint > Current Waypoint Number \
15.Current Flight Mode 
### Geofence 
The virtual boundary that restrict the vehicle from flying into unsafe or restricted zone. 
### Types of Geofence
**1.Cylindrical Fence :** Circular boundary to restrict the vehicle. \
**2.Polygonal Fence :** Linear boundary that is useful to fly a vehicle into desired area and shape. \
![image link](https://github.com/Vishalpolicepatil/Report-level-2/blob/main/Screenshot%202025-09-04%20220521.png?raw=true) \
[click here](https://youtu.be/l0WbwB-BPwc?t=9) to view video of performing the virtual mission. 
### Saving Mission in Mission Planner 

We can make a plan in mission planner in plan window and save in the floders and we can open it any time by clicking **Load WP file** \
![image link](https://github.com/Vishalpolicepatil/Report-level-2/blob/main/Screenshot%202025-09-06%20105701.png?raw=true)
### Surveying 
Surveying is feature of mission planner in which the vehicle captures the photo and video of the area. \
![image](https://github.com/Vishalpolicepatil/Report-level-2/blob/main/Screenshot%202025-09-08%20140716.png?raw=true) \
[click here](https://youtu.be/j2uY_Qz1X2Q) to watch the video of surveying in mission planner 
### Advance Flight Planning 
#### Survey on multiple location 
Simultaneous survey over the two separate grids \
![image](https://github.com/Vishalpolicepatil/Report-level-2/blob/main/Screenshot%202025-09-08%20154745.png?raw=true)

### Loiter 
Loiter is drone flight mode that uses the **GPS** to hold the drone's current position, altitude, and heading, by stopping it in the mid air.

# TASK 4 : Flight Data Logging & Analysis
**Objective :** To explore the methodology behind air crash investigations and learn how aviation safety evolves from past incidents. \
**Task :**
### LOGS 
**Logs** are recording's of flight data. \
There are two types of log analysis they are :
1. Telemetry Logs : Requires a real time connection to computer. 
2. Dataflash Logs : On flight controller during flight. \
Some Dataflash log have internal memory and some of them require an removable SD card. 
### DATA FLASH LOGS 
We can excess the **DATA FLASH LOGS** in mission planner in flight data tab under the HUD(Heads up display) 
![alt text](https://github.com/Vishalpolicepatil/Report-level-2/blob/main/Screenshot%202025-09-30%20201725.png?raw=true)
- On clicking *download data flash logs* it shows the option to download the recording's of the previous flights. 
- **Auto Analysis** option enables mission planner to analyse and summary will be provided after analysis. \
This is one of Auto analysed data of my flight 
![alt text](https://github.com/Vishalpolicepatil/Report-level-2/blob/main/Screenshot%202025-09-30%20203259.png?raw=true)
- **Review a log** option enables us to provide information about the actual path and what went wrong in case of crash and plot graphs.   

### SIMULATOR LOG FILES 
#### Auto Analysis 
![alt text](https://github.com/Vishalpolicepatil/Report-level-2/blob/main/Screenshot%202025-10-19%20091711.png?raw=true)
#### Altitude vs Time 
![alt text](https://github.com/Vishalpolicepatil/Report-level-2/blob/main/Screenshot%202025-10-19%20092117.png?raw=true)
The pink shade shows the drone is in the stable mode i.e disarmed condition and red color pop-up message (drone is in the auto mode) i.e armed mode. The drone followed the path which was fed in the FC(flight controller) and reached a peak of 150 m.
#### Throttle vs Time 
![alt text](https://github.com/Vishalpolicepatil/Report-level-2/blob/main/Screenshot%202025-10-19%20093648.png?raw=true)
The maximum throttle is 0.48, when the drone reached to it's maximum altitude. 
#### Battery Consumption vs Time 
![alt text](https://github.com/Vishalpolicepatil/Report-level-2/blob/main/Screenshot%202025-10-19%20094716.png?raw=true)
The current started draining after the drone is armed and started flying.
#### Battery Voltage vs Time 
![alt text](https://github.com/Vishalpolicepatil/Report-level-2/blob/main/Screenshot%202025-10-19%20095038.png?raw=true) 
The drone consumes 12.6 v throught the flight. 
#### Velocity vs Time
![alt text](https://github.com/Vishalpolicepatil/Report-level-2/blob/main/Screenshot%202025-10-19%20095322.png?raw=true)
The peak velocity is 10 m/s and dropped consecuvently. 
### CRASH LOG FILES 
#### Auto Analysis 
![alt text](https://github.com/Vishalpolicepatil/Report-level-2/blob/main/Screenshot%202025-10-19%20095737.png?raw=true)

Compass Calibration - fail, means the drone operation is not done properly. 
#### Altitude vs Time 
![alt text](https://github.com/Vishalpolicepatil/Report-level-2/blob/main/Screenshot%202025-10-19%20100253.png?raw=true)
Calibration is not done properly in the FC(flight controller). 
#### Throttle & Battery vs Time 
Due to faulty calibration the trottle and battery is not obtained in the log files. 
#### Velocity vs time 
Due to faulty calibration the velocity data has not been recorded in the log files.
### AMS LOG FILES 
#### Auto Analysis 
![alt text](https://github.com/Vishalpolicepatil/Report-level-2/blob/main/Screenshot%202025-10-19%20101316.png?raw=true)
#### Altitude vs Time 
![alt text](https://github.com/Vishalpolicepatil/Report-level-2/blob/main/Screenshot%202025-10-19%20130209.png?raw=true)
![alt text](https://github.com/Vishalpolicepatil/Report-level-2/blob/main/Screenshot%202025-10-19%20101539.png?raw=true)
Difference Between the CTUN.Alt and AHRS.Alt 

| **Aspect** | **CTUN Altitude** | **AHRS Altitude** |
|-------------|-------------------|-------------------|
| **Definition** | The vehicle's most accurate and dynamic estimate of its altitude, calculated by the Extended Kalman Filter (EKF). | The altitude component of the AHRS is primarily based on the barometer, which measures air pressure. |
| **Sensor Data Used** | The EKF fuses data from multiple sensors, including the Inertial Measurement Unit (IMU), Global Positioning System (GPS), and the barometer. | Based mainly on the onboard barometer. |
| **Purpose/Usage** | Used internally by the autopilot for all altitude-controlled flight modes, such as *AltHold*, *Loiter*, and *Auto*. For instance, in *AltHold*, the autopilot compares `CTUN.Alt` with `CTUN.DAlt` to adjust throttle and maintain altitude. | In older firmware versions or when the EKF is not functioning properly, the system may rely more heavily on the barometer for altitude estimation. |
#### Throttle vs Time Consumption 
![alt text](https://github.com/Vishalpolicepatil/Report-level-2/blob/main/Screenshot%202025-10-19%20131617.png?raw=true)
- Bat.volt moniters the performance of the battery.
- CurrTot - Total current consumed over a time.
- **Throttle Hover(Tho)** : Actual throttle required by the drone to hover. 
#### Battery voltage vs Time 
![alt text](https://github.com/Vishalpolicepatil/Report-level-2/blob/main/Screenshot%202025-10-19%20132939.png?raw=true)
#### Velocity vs Time 
![alt text](https://github.com/Vishalpolicepatil/Report-level-2/blob/main/Screenshot%202025-10-19%20133141.png?raw=true)
# TASK 5 : Advanced PID Tuning 
**Objective :** To develop a strong understanding of PID controllers and their application in UAV stability and autonomous control systems. \
**Therotical Foundation :** \
A PID controller  (Proportional–Integral–Derivative) forms the backbone of flight control systems, maintaining stable, responsive, and autonomous flight. \
![alt text](https://github.com/Vishalpolicepatil/Report-level-2/blob/main/Screenshot%202025-10-25%20115600.png?raw=true)
## Real-Life Example for using PID in Aviation 
Consider a drone hovering at a fixed altitude:
1. Goal (Setpoint): Maintain a height of 10 m above ground. 
2. Sensors: An altimeter or barometer measures the current altitude.
3. Error: Suppose the drone drifts down to 9.8 m; error = 0.2 m.

PID Response:

P-Term: Increases throttle proportionally to the 0.2 m error.

I-Term: Accumulates previous altitude errors to counter persistent descent (e.g., due to wind).

D-Term: Detects how fast the drone is falling and adds anticipatory correction to slow descent.

Result: Motor speed increases just enough to restore the drone to 10 m, then stabilizes.​

This constant feedback ensures smooth hovering, with thousands of PID computations per second on modern flight controllers like Betaflight or Ardupilot.
## Real world Example 
An agricultural spraying drone uses cascaded PIDs to stay steady despite external forces:

- When wind pushes it sideways, the roll PID reacts immediately.

- Long-term drift from uneven spray weight is handled by the integral term.

- Sudden wind gusts are mitigated by the derivative component, damping rapid oscillations.
- This ensures consistent spray coverage, crucial in precision agriculture.




**THANK YOU**
