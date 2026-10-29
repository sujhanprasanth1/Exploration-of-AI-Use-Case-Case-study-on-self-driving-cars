# Exploration-of-AI-Use-Case-Case-study-on-self-driving-cars

# AIM
To study the application of Artificial Intelligence (AI) in self-driving cars and understand how AI technologies help vehicles perceive their surroundings, make decisions, and navigate safely without continuous human control.
# THEORY

A self-driving car, also called an autonomous vehicle, is a vehicle that can sense its surroundings, make driving decisions, and control its movement with little or no human intervention. It uses AI to perform tasks normally done by a human driver, such as observing the road, identifying obstacles, predicting traffic behavior, and steering safely.

The main AI technologies used in self-driving cars are:

Computer Vision: Uses cameras and deep-learning models to detect lanes, traffic signals, road signs, pedestrians, cyclists, and other vehicles.

Sensor Fusion: Combines data from cameras, radar, LiDAR, GPS, and other sensors to create a complete and reliable view of the environment.

Machine Learning and Deep Learning: Learns from large amounts of driving data to recognize objects, predict movements, and improve driving decisions.

Localization: Determines the exact position of the vehicle using GPS, maps, and real-time sensor data.

Prediction: Estimates the likely movement of nearby vehicles, pedestrians, and cyclists.

Path Planning: Selects a safe and efficient route, speed, lane, and steering trajectory.

Control Systems: Converts decisions into physical actions such as acceleration, braking, and steering.

# Working Principle
Self-driving cars work through a continuous cycle: Sense → Perceive → Predict → Plan → Act.

Sensing the environment:
The vehicle collects real-time data using cameras, radar, LiDAR, GPS, and ultrasonic sensors. Cameras provide visual information, radar measures speed and distance, and LiDAR creates a 3D map of nearby objects using laser reflections.

Sensor fusion:
AI combines data from all sensors to reduce errors and improve reliability. For example, cameras identify the color of a traffic light, while LiDAR provides the distance and shape of nearby objects.

Object detection and perception:
Deep-learning models analyze the sensor data to identify roads, lanes, vehicles, pedestrians, cyclists, traffic signs, signals, and obstacles. This helps the car understand its surroundings.

Localization and mapping:
The car determines its exact position using high-definition maps, GPS, and live sensor data. This helps it know its lane, direction, and distance from the destination.

Prediction of road-user behavior:
AI predicts the possible movement of nearby objects. For example, it estimates whether a pedestrian may cross the road or whether another vehicle may change lanes.

Path planning and decision-making:
Based on the detected objects and predicted movements, the AI system selects the safest action. It decides the required speed, lane position, braking distance, turning angle, and route.

Vehicle control:
The planned decision is sent to the control system, which operates the steering, accelerator, and brakes. This process is repeated continuously to respond to changing road conditions.

## Example
If a self-driving car approaches a pedestrian crossing, its cameras and LiDAR detect the pedestrian. Sensor fusion confirms the pedestrian’s position and distance. AI predicts that the pedestrian may cross the road, so the path-planning system decides to slow down or stop. The control system then applies the brakes. After the pedestrian crosses safely, the car resumes driving.
<img width="693" height="869" alt="image" src="https://github.com/user-attachments/assets/92b600d4-b91f-4c73-bc42-a9cb4b0e97af" />


# Result
The study shows that self-driving cars use AI to perform the major functions of human driving: sensing the environment, recognizing objects, predicting movement, planning a safe route, and controlling the vehicle. Cameras, radar, and LiDAR provide environmental data, while AI and machine learning convert this data into safe driving decisions in real time.

