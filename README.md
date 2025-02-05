## Overview  
This project is an **Arduino-based robot** designed to **follow lines and solve mazes** using **infrared sensors** for line detection and an **ultrasonic sensor** for obstacle avoidance. 

## Hardware Components  
- **Arduino** (any compatible model)  
- **Infrared Sensors (IR)** – for line detection  
- **Ultrasonic Sensor** – for obstacle detection  
- **DC Motors** – for movement  
- **LED** – for calibration indication  
- **Power Supply & Wiring**  

## Features  

### 1. Line Following  
- Uses **five IR sensors** to detect black (line) and white (background) surfaces.  
- Sensors are **calibrated** to determine threshold values for accurate tracking.  

### 2. Maze Solving  
- Implements a **basic maze-solving algorithm** using IR and ultrasonic sensors.  
- **Ultrasonic sensor** measures distances and helps the robot avoid obstacles.  

### 3. Obstacle Avoidance  
- The robot **stops or reroutes** when an obstacle is detected within a certain distance.  

## How It Works  

1. **Sensor Calibration** – The robot calibrates its IR sensors to differentiate between the black line and white background.  
2. **Line Following** – Motor speeds adjust based on sensor input to follow the line smoothly.  
3. **Maze Navigation** – The robot detects intersections and makes decisions to solve the maze.  
4. **Obstacle Avoidance** – The ultrasonic sensor prevents collisions by adjusting the robot’s path.  

## Code Breakdown  
- **Infrared Sensors** – Calibrate and detect line positions.  
- **Motors** – Control movement and turning.  
- **Ultrasonic Sensor** – Detects obstacles and prevents collisions.  

## Calibration Process  
1. Turn on the robot; the **LED** indicates calibration mode.  
2. The robot scans the black and white surfaces to determine sensor threshold values.  
3. After calibration, the robot begins line-following mode.  


## Future Improvements  
- **Dynamic Speed Optimization** – Adjusting speed based on track complexity.  
- **Enhanced Maze Solving** – Implementing more advanced algorithms.  
- **Improved Obstacle Avoidance** – Developing a more robust collision detection system.  
