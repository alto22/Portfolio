# An_Ensemble_Approach_for_Anomaly_Detection_in_Hand-Mounted_PCB_Components


> MSc Business Administration and Data Science

> Submission Date: 15.05.24


## Authors
- Aleksander Torp
- Frederik Gøtske


## Abstract

In collaboration with a small-scale PCB manufacturer, this thesis explores the design and implementation of a cost-efficient hardware and software setup for anomaly detection in hand-mounted PCB components. Recognizing the unique needs of such manufacturers, this research develops a customized automated optical inspection system that incorporates multiple one-class Convolutional Autoencoder models, each specialized for detecting anomalies in a specific type of PCB components, without requiring anomaly images for training. These are supported by a YOLOv8-based cropping method that accurately identifies and isolates components of interest. The system achieves an F1-Score of 0.99 with a training set of 200 images, illustrating the system’s potential adaptability and accuracy across various PCB designs. The full research process is documented, extensively covering the data collection, model training, evaluation, and deployment phases. The study also features the insights learned from the transition from a simplistic camera setup, susceptible to frequent errors and inconsistencies, to a stable and consistent imaging system. The improved imaging capability, combined with the tailored approach of using specialized models provides a flexible, scalable and economically viable solution for enhancing quality control in PCB manufacturing, addressing both the cost concerns and the technical requirements of the manufacturer. Finally, the proposed system is split into a training and operational pipeline for easy deployment and further development. 

Keywords: Computer Vision, Anomaly Detection, YOLO, Python, Autoencoders, Printed Circuit Boards
