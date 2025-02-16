# Computer-Vision-Based-Advanced-Fire-Prevention-System-for-Methanol-Powered-Ships

# Cargo Type Prediction and Notification System for Port Entry

## Languages:
- **Python**

## Important Libraries:
- **Pandas**
- **NumPy**
- **Matplotlib**
- **OpenCV**

## Technologies:
- **Data Analysis**
- **Computer Vision**
- **Unsupervised Learning**
- **Image Processing**
- **Video Processing**

# Advanced Fire Prevention System for Methanol-Fuelled Ships

## Abstract
This project focuses on developing an computer vision based advanced fire prevention system for methanol-fuelled ships, addressing the unique safety challenges posed by methanol's nearly invisible flames and high flammability. The system integrates thermal imaging for heat detection and gas sensors for methanol vapor monitoring, with a centralized alert and shutdown mechanism. By continuously monitoring high-risk areas like the pump room, the system aims to enhance fire safety, protect crew members, and safeguard the vessel.

## Dataset
Web images for demonstration

## Methodology
1. **Heat Detection**: A thermal imaging camera captures real-time video of the pump room. A Python-based program processes the video frame-by-frame to detect temperature anomalies and potential hotspots.
2. **Flammable Gas Monitoring**: Gas sensors continuously measure methanol vapor concentrations. When concentrations exceed 20% of the Lower Explosion Limit (LEL), an alert is triggered.
3. **System Integration**: The outputs from the heat detection and gas monitoring systems are integrated into a central unit. The unit manages alerts and initiates an automated shutdown of the pump room if both heat and gas levels exceed critical thresholds.

## Models
1. **Thermal Imaging System**: Utilizes a Python program to analyze thermal video frames and detect hotspots. The program processes frames at regular intervals and generates alerts when temperature thresholds are exceeded.
2. **Gas Detection System**: Employs electrochemical or infrared gas sensors to monitor methanol vapor concentrations. The system triggers alerts when vapor levels reach dangerous thresholds.
3. **Centralized Alert and Shutdown System**: Integrates inputs from the thermal imaging and gas detection systems. It activates alerts for individual hazards and initiates an automated shutdown if both hazards are detected simultaneously.

## Results and Conclusion
The integrated fire prevention system demonstrates a proactive approach to mitigating fire risks in methanol-fuelled ships. The thermal imaging system effectively detects temperature anomalies, while the gas monitoring system provides real-time alerts for methanol vapor concentrations. The centralized unit ensures timely responses by activating alerts and shutting down the pump room in critical scenarios. This system enhances fire safety in high-risk areas and can be adapted to other parts of the ship. Future improvements could focus on refining sensor calibration and enhancing system performance in varying environmental conditions.

## Disclaimer
The Advanced Fire Prevention System for Methanol Ships is designed for demonstration purposes and may require further development and testing to ensure reliability and effectiveness in real-world scenarios. The accuracy of heat detection, gas monitoring, and system integration depends on various factors, including sensor calibration and environmental conditions. Further validation and refinement are necessary to ensure reliability and effectiveness in practical applications.
