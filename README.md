# NASA-SpaceApps-2024 - Seismic Detection
Developed a new algorithm to detect the timestamp of the start of seismic activity.

## About the Team
We are a university team from Guanajuato aiming to solve the challenge of detecting seismic events in space.  
With this project, we apply our knowledge of Machine Learning and Deep Learning.

## About the Challenge
Planetary seismology missions struggle with power limitations when sending continuous seismic data back to Earth. However, only a fraction of this data is scientifically useful! Instead of transmitting all recorded data, what if a lander could distinguish meaningful seismic events from noise and send back only relevant information?

Your challenge is to write a computer program that analyzes real seismic data from the Apollo missions and the Mars InSight Lander to identify seismic quakes within the noise.

---

# Team Name: The Last Dans

## High-Level Summary
Our project implements a **signal-enhancement algorithm** to improve efficiency in detecting seismic events.  
The goal is to identify the **exact start time** of a seismic event from a recorded signal file, reducing the amount of transmitted data.  
### **Why is this important?**
- A **single day's** worth of seismic data can be **40 MB** in size.
- NASA's Mars landers transmit data at **2 MB per second** but send multiple types of data, such as images, which take **30 minutes to several hours** to transmit depending on resolution.
- By **precisely detecting seismic events**, we can **reduce unnecessary data transmission**, optimizing communication time and bandwidth.

## Project Demo
🔗 [GitHub Repository](https://github.com/jafetcc02/NASA-SpaceApps-2024---Seismic-Detection)

## Project Details
**Problem:**  
The challenge is to determine the **exact timestamp** of the start of a seismic event within a signal data file.


