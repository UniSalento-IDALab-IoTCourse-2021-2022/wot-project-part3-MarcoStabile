**Neurodegenerative Diseases: Patient Monitoring System with Anomaly Detection**

LINKS : 
https://github.com/UniSalento-IDALab-IoTCourse-2021-2022/wot-project-part1-MarcoStabile
https://github.com/UniSalento-IDALab-IoTCourse-2021-2022/wot-project-part2-MarcoStabile

**THIRD PART: DASHBOARD**

This is an Internet of Things (IoT) application designed to monitor and manage patient well-being through a combination of BLE beacon scanning and wearable device anomaly detection.
Wearable device anomaly detection is not the main focus of this educational project, that is the beacon detection.
The project leverages the Web of Things (WoT) paradigm to enhance device interoperability and create a real-time monitoring system.

In healthcare environments, timely and accurate information is crucial for ensuring patient safety. 
The project employs a Raspberry Pi as an edge device to scan for BLE beacons in the surroundings and communicate with a wearable device worn by the patient. 
The wearable device is equipped with sensors to monitor vital signs and detect anomalies such as falls. Seen that the main focus is the detection , anomalies and all the 
sensors data are simulated.

<img width="230" alt="image" src="https://github.com/UniSalento-IDALab-IoTCourse-2021-2022/wot-project-part3-MarcoStabile/assets/105797309/d8b0b35a-f166-46a9-b983-45082e9de108">

Once the dashboard is opened this is the main page:

<img width="438" alt="image" src="https://github.com/UniSalento-IDALab-IoTCourse-2021-2022/wot-project-part3-MarcoStabile/assets/105797309/b7e768ad-e801-407d-a4f1-7e0e36e10bea">

So the patient list with their main information is displayed and there are two buttons. One is to get the last anomaly detected for that patient and the other one is to get his latest position.
On the top left there is a button "Add patient" that gives the possibility of adding a new patient.
On the top right there is a button that allows to see the anomaly history, because it could happen that some anomalies are missed if the dashboard was not open in that particular moment.
