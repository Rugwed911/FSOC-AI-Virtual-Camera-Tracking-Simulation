# FSOC-AI-Virtual-Camera-Tracking-Simulation
Development of an AI-Based Virtual Camera Tracking System for Coarse Alignment of Mobile Free Space Optical Communication (FSOC) Terminals.


## Project Overview

This project develops a software-based virtual camera tracking system
for coarse alignment of mobile FSOC terminals.

The simulation combines:

- Virtual camera / FPA
- YOLO-based beacon detection
- Centroid extraction
- Kalman filtering
- Camera-motion compensation
- Velocity feed-forward
- Pan/tilt control
- Target acquisition and reacquisition
- Environmental disturbances

## Final Results

| Metric | Result |
|---|---:|
| YOLO Detection Rate | 100% |
| Mean Tracking Error | 6.079 px |
| RMSE | 9.534 px |
| Maximum Error | 73.322 px |
| ≤10 px Lock | 95.33% |
| Average Trajectory Lock | 97.20% |
| Effective YOLO FPS | 7.99 FPS |

## Demonstration

[Watch the simulation video]
https://drive.google.com/file/d/1oQAwY9Fyr9WVFjuY2QHdQe-CEQ_0k033/view?usp=sharing

## Project Notebook

[Open Google Colab Notebook]
https://colab.research.google.com/drive/1gS067e92a0f0jQh9fF7vkfhQwj8mRCEb?usp=sharing

## Documentation
  [FSOC_Simulation_Final_Data_Black_Theme.pdf](https://github.com/user-attachments/files/33051105/FSOC_Simulation_Final_Data_Black_Theme.pdf)
