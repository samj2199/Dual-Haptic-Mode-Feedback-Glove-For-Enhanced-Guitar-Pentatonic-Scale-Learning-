# Dual Mode Haptic Feedback Glove for Enhanced Guitar Learning (Theoretical Concept)
## Overview
The Dual Mode Haptic Feedback Glove project is a theoretical concept developed in ROS(Robotics Operating System) which theoretically combines haptic technology and artificial intelligence to revolutionize guitar learning. By providing real-time tactile feedback, the glove helps learners understand and correct their playing, enhancing technique retention and reducing dropout rates among beginners trying to learn the tabs of a pentatonic scale.

## Features
- Haptic Feedback: Delivers positive reinforcement for correct notes and corrective feedback for errors.
- Machine Learning Integration: Uses advanced models such as KNN, CNNs, Siamese Networks, and XGBoost for analyzing guitar note accuracy.
- Feature Extraction: Employs Librosa and OpenSmile for extracting audio features like Mel Spectrograms to assess musical similarity.
- Dual Mode Functionality: Offers both passive and active feedback modes for comprehensive learning experiences.
  
## Motivation
Traditional guitar learning methods often lack interactivity and immediate feedback, leading to high attrition rates. Inspired by projects like MIT's "Move Me," this project aims to streamline guitar learning through innovative technology that embeds correct techniques into muscle memory more effectively.

## Methodology
- Feature Extraction: Utilizes MFCCs and other audio features for analyzing guitar pentatonic notes from tracks.
- Model Development: Implements a variety of machine learning algorithms to evaluate note accuracy and provide feedback.
- Haptic Feedback: Integrates tactile responses based on musical analysis to guide learners in real time.
  
## System Design
- Glove Architecture: Features embedded sensors like flex sensors, accelerometers, and gyroscopes to detect hand movements and orientation.
- Data Processing: Utilizes ROS/Gazebo and Blender for simulation and modeling of the glove's interaction with guitar strings.
  
## Implementation
- Model Creation: Here we took a hit since there isn't an actual Pentatonic scales dataset in order to test our theory on.
- Sensor Integration: Incorporate vibration motors to provide feedback based on the analysis of musical inputs.

- In order to still test our theory we went ahead and recorded custom guitar pentatonic scales where we did multiple versions with the right scales and the wrong scales played deliberately in order to test our theory. But this is not eniugh data to test our theory.
  
## Results
While the project is theoretical, we could not achieve success in simulating our glove since our ML aspect of the project was left unfinished due to lack of data. Any contributions or suggestions are welcome. Please fork the repository and submit pull requests with enhancements or new features. 

Future Work
Further development will focus on refining machine learning models and enhancing the glove's adaptability to various learning styles. Additional collaborations and research will explore the broader applications of this technology in skill-based learning.

## References
- MIT's Move Me Project
- Librosa and OpenSmile for Audio Processing
- Haptic Feedback Research in Virtual Reality
