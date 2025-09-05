# Bicycle-Drive-Robot-Kinematics-Simulator
Forward and Inverse Kinematics Simulators for a Bicycle Drive Robot. Includes a slider-controlled forward kinematics simulator and a mouse-click-based inverse kinematics simulator, implemented in Python with Matplotlib for robotics education and research.



This repository provides forward and Inverse Kinematics simulators for a Bicycle Drive Robot.  
The bicycle model is a widely used abstraction for car-like robots in motion planning and control research.  

This project includes two interactive modes:

- Forward Kinematics Simulator
  Control the robot’s velocity and steering angle using sliders to visualize its trajectory in real time.  

![image alt](https://github.com/aAfeworki/Bicycle-Drive-Robot-Kinematics-Simulator/blob/main/Forward_Kinematics_Simulator_for_Bicycle_Drive.png?raw=true)

- Inverse Kinematics Simulator
  Click a target point on the workspace, and the robot computes steering and velocity inputs to reach the goal.  

![image alt](https://github.com/aAfeworki/Bicycle-Drive-Robot-Kinematics-Simulator/blob/main/Inverse_Kinematics_for_Bicycle_Drive.png?raw=true)


✨ Features

    - 🎚️ Forward Kinematics controlled with sliders  
    - 🖱️ Inverse Kinematics controlled via mouse-click target input  
    - 📈 Real-time trajectory visualization with Matplotlib  
    - 📚 Educational tool for robotics and motion planning courses  
    - 🔧 Easy to extend for autonomous driving research  





Requirements:

    Python 3.8+

    NumPy

    Matplotlib

    Tkinter (pre-installed with most Python distributions)



🚀 Usage

    - Forward Kinematics Simulator
Run:
python forward_kinematics.py

Use sliders to control the velocity and steering angle.

Observe the resulting motion of the bicycle model.


    - Inverse Kinematics Simulator

Run:
python inverse_kinematics.py

Click anywhere on the workspace to set a target position.

The simulator computes steering and velocity inputs to drive toward the target.




📚 Background

    The Bicycle Model is a simplification of Ackermann steering, where the two front wheels are abstracted as one virtual wheel.
    Forward Kinematics: Calculates the trajectory of the robot given velocity and steering inputs.

    Inverse Kinematics: Determines the required control inputs to reach a given target.

    This project provides an interactive educational platform to study bicycle kinematics, commonly used in autonomous vehicle research.

🤝 
Contributions are welcome!
Open issues for bugs or feature requests


Submit pull requests for improvements



📜 License
This project is licensed under the MIT License.

👨‍💻 Author
Developed by Afework Alemu ✨
If you find this project useful, please give it a ⭐ on GitHub!
