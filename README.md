# Pedaling Through KAIST: A Computerized Assessment of Bike-Friendliness
Our team aims to develop a comprehensive map of KAIST's road infrastructure, utilizing advanced GIS software and a sophisticated rating system. The map will display a detailed analysis of the road network, highlighting areas that are more conducive to cycling as well as areas that may pose potential hazards or obstacles for cyclists.

By creating this map, we seek to empower cyclists with valuable information to help them choose the safest and most efficient routes. The map's rating system will evaluate various factors that affect cycling conditions, such as traffic volume, road quality, and gradient. These factors will be scored to identify the most bike-friendly routes.

Special Topics in Smart Convergence [Smart Mobility for Sustainable Society] (CoE491_EE488_CS492)

Team 3 Yeskendir Assankul, Lia Lee, Muhammad Ahmed, Geunyong Park
https://youtu.be/nVbi6dfEoXo

## Previous work
The satisfaction of bicycle users with KAIST's current infrastructure was assessed through a computer-visual analysis and interviews.

The computer-visual analysis measured the difficulty of movement for road users, such as maneuvers, turns, speed, and transitioning to a lane not meant for cyclists.

Assessing the infrastructure for cyclists and pedestrians is crucial as it is closely linked to accident risks.

Data was collected through recordings to determine various parameters for a rating system.

## Final idea
Our team aims to develop a comprehensive map of KAIST's road infrastructure, utilizing advanced GIS software and a sophisticated rating system. The map will display a detailed analysis of the road network, highlighting areas that are more conducive to cycling as well as areas that may pose potential hazards or obstacles for cyclists.

By creating this map, we seek to empower cyclists with valuable information to help them choose the safest and most efficient routes. The map's rating system will evaluate various factors that affect cycling conditions, such as traffic volume, road quality, and gradient. These factors will be scored to identify the most bike-friendly routes.

## Bicycle Road Rating System (BRRS)
BRRS is a system that can be used by city planners, transportation officials, and other stakeholders to evaluate existing bicycle infrastructure and identify areas that need improvement. 

By using the BRRS, these stakeholders can work to create safer and more enjoyable cycling experiences for everyone.


Parameters:
Satisfaction of users (Survey)
Accessibility of bicycle lanes (Computer Vision analysis)
Roughness of the road (Mobile application)

## Satisfaction of users (Survey)
We conducted an additional survey to find bicycle riders’ satisfaction with the five bicycle roads in KAIST.

The five bicycle roads are roads that are often used by students when going to classes, dormitory, or side gate.

## Accessibility of bicycle lanes (Computer Vision analysis)
We used a quadcopter to capture videos of two out of five designated bicycle roads at our university.

We applied YOLOv8+DeepSORT, a state-of-the-art object detection and tracking algorithm, to detect and track unique objects, in our case, bicycles.

We tracked whether the bicycles were on the designated bicycle paths and increased the counter of Total Violations if they were not.

We collected the number of Total Violations in a ten-minute interval during the rush hour as a parameter for the Bicycle Road Rating System (BRRS).

We also normalized the number of Total Violations before introducing it to the BRRS equation.
![image](https://github.com/Yeskendir2502/PedalingThroughKAIST_SmartMobilityforSustainableSociety/assets/61699877/b5ed10d4-b3a5-481a-b5f8-cd28500fb347)

## Roughness of the road (Mobile application)
![image](https://github.com/Yeskendir2502/PedalingThroughKAIST_SmartMobilityforSustainableSociety/assets/61699877/60f137bf-5081-470e-b6d0-50ae9098ca6a)

![image](https://github.com/Yeskendir2502/PedalingThroughKAIST_SmartMobilityforSustainableSociety/assets/61699877/976a067e-a43d-475d-8d46-fe4fac9f7c33)




## Poster
![Poster](https://github.com/Yeskendir2502/PedalingThroughKAIST_SmartMobilityforSustainableSociety/assets/61699877/cbdd0a8a-d8c3-4e69-b641-a6f5a8afa667)
