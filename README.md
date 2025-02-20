# Holonomic-Art-Bot

### **Theme Introduction**
In the heart of a lush Greenland landscape lies a timeless mystery: the Nasca Lines. These colossal geoglyphs, spanning vast stretches of green land, have confounded archaeologists and historians for centuries. The intricate animal figures, geometric designs, and mysterious shapes etched into the Earth's surface represent the marvel of a bygone civilization. Yet, their true purpose remains elusive. 

Were these lines celestial calendars aiding agriculture? Sacred pathways for rituals? Messages for extraterrestrial beings? Theories abound, but the mystery remains, challenging our understanding of ancient cultures and their relationship with the cosmos.

![geoglyph](https://github.com/user-attachments/assets/5b210ef0-b108-4f4c-9c7d-96a323de23d5)
*Caption: Ancient geoglyphs showcasing intricate designs, inspiring modern robotic creations.*

### **Project Inspiration**
Taking inspiration from these marvels, the Holonomic-Art-Bot project reimagines the creation of geoglyphs using modern robotics. Our aim is to create an 8ft x 8ft arena where a team of three holonomic drive robots autonomously collaborates to draw intricate glyphs, aided by an overhead camera system.

---

## **Features**
- **Holonomic Drive Locomotion**: Enables precise movement and control to draw intricate patterns.
- **Overhead Camera Assistance**: Real-time localization and guidance for the robots.
- **Collaborative Multi-Robot System**: Coordination between three robots to create complex geoglyphs.
- **Simulation and Real-World Implementation**: Concepts tested in simulation before hardware execution.

---

## **Getting Started**

### Prerequisites
1. Basic knowledge of robotics and kinematics.
2. Familiarity with programming languages like Python and C++.
3. Tools and software for robot simulation (e.g., Gazebo, ROS).
4. Hardware components:
   - Three holonomic drive robots
   - Overhead camera system
   - Communication modules (e.g., ESP32 or XBee modules)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/holonomic-art-bot.git
   ```
2. Navigate to the project directory:
   ```bash
   cd holonomic-art-bot
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

---

## **Project Structure**
```
holonomic-art-bot/
├── simulations/         # Simulation files and configurations
├── hardware/            # CAD models, schematics, and hardware assembly guides
├── src/                 # Source code for the robots
├── docs/                # Documentation and project reports
├── media/               # Images and videos of the robots in action
├── README.md            # Project overview (this file)
└── requirements.txt     # Python dependencies
```

---

## **Implementation Steps**
1. **Understand Holonomic Drive**:
   - Study the kinematics of holonomic robots.
   - Simulate basic movement patterns in software.

2. **Develop Motion Controllers**:
   - Write and test algorithms for curve-following motions.
   - Implement PID controllers for precise movement.

3. **Build Robots**:
   - Design and fabricate the robots.
   - Integrate motors, sensors, and communication modules.

4. **Establish Communication**:
   - Set up reliable communication between robots and the central computer.

5. **Implement Localization**:
   - Use the overhead camera for real-time localization.
   - Write code for accurate position tracking and correction.

6. **Test and Optimize**:
   - Run simulations and compare with real-world performance.
   - Refine designs based on observed challenges.

---

## **Technologies Used**
- **Programming Languages**: Python, C++
- **Simulation Tools**: Gazebo, ROS
- **Hardware**: ESP32, XBee modules, omnidirectional wheels
- **Camera System**: OpenCV for vision processing

---

## **Challenges Faced**
1. Designing and fabricating robust and aesthetic robots.
2. Establishing reliable communication in real-world conditions.
3. Implementing accurate localization with a non-ideal overhead camera.
4. Achieving smooth and coordinated movements between the robots.

---

## **Future Scope**
- Expand the project to larger arenas.
- Enhance glyph complexity and precision.
- Integrate machine learning for improved motion planning.
- Use drones for overhead localization and extended coverage.

---

## **Contributors**
- Aditya Kumar Ray ([GitHub Profile](https://github.com/AdityaKumarRay))
- Sandeep Kumar Das ([GitHub Profile](https://github.com/Sandeep-622))
- Saumit Pradhan

---

## **Acknowledgments**
This project was inspired by the ancient Nasca Lines and the theme of Hologlyph Bots. Special thanks to all team members, mentors, and organizations that supported this project.

---

## **License**
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## **Media**
- Images and videos of the project can be found in the `media/` folder.

---

**Happy Learning and Innovating!**

