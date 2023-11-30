# Humanoid Robot Omni-direction Walking Pattern Generation using ZMP Analytical

>This is an implementation of an omni-direction walking pattern generator for humanoid robots using the ZMP analysis approach referenced from [Eko Rudiawan](https://github.com/ekorudiawan) and was proposed by Harada, Kensuke, et al. The inputs are defined as movement commands $cmd_x$, $cmd_y$, $cmd_\theta$, which will represent the next position and orientation of swing foot, generates CoM, left foot and right foot trajectories written from world coordinates. This code can be implemented on a real robot by adding an inverse kinematics solver.

### Turning + diagonal walking with motion command $cmd_x = 0.03$, $cmd_y = 0.01$, and $cmd_a = 0.01$

![Result](https://github.com/charlierolando/Humanoid-Robot-Omni-direction-Walking-Pattern-Generation-using-ZMP-Analytical/blob/main/images/images1.png)

>Click [this](https://github.com/charlierolando/Humanoid-Robot-Omni-direction-Walking-Pattern-Generation-using-ZMP-Analytical/blob/main/images/images1.png) when the image doesn't appear

### Forward walking with motion command $cmd_x = 0.03$, $cmd_y = 0.00$, and $cmd_\theta = 0.00$

![Result](https://github.com/charlierolando/Humanoid-Robot-Omni-direction-Walking-Pattern-Generation-using-ZMP-Analytical/blob/main/images/images2.png)

>Click [this](https://github.com/charlierolando/Humanoid-Robot-Omni-direction-Walking-Pattern-Generation-using-ZMP-Analytical/blob/main/images/images2.png) when the image doesn't appear

### Reverse walking with motion command $cmd_x = -0.03$, $cmd_y = 0.00$, and $cmd_\theta = 0.00$

![Result](https://github.com/charlierolando/Humanoid-Robot-Omni-direction-Walking-Pattern-Generation-using-ZMP-Analytical/blob/main/images/images3.png)

>Click [this](https://github.com/charlierolando/Humanoid-Robot-Omni-direction-Walking-Pattern-Generation-using-ZMP-Analytical/blob/main/images/images3.png) when the image doesn't appear

### Diagonal walking with motion command $cmd_x = 0.03$, $cmd_y = -0.01$, and $cmd_a = 0.00$

![Result](https://github.com/charlierolando/Humanoid-Robot-Omni-direction-Walking-Pattern-Generation-using-ZMP-Analytical/blob/main/images/images4.png)

>Click [this](https://github.com/charlierolando/Humanoid-Robot-Omni-direction-Walking-Pattern-Generation-using-ZMP-Analytical/blob/main/images/images4.png) when the image doesn't appear

## [Code:](#code)

>Click [this](https://github.com/charlierolando/Humanoid-Robot-Omni-direction-Walking-Pattern-Generation-using-ZMP-Analytical/blob/main/gait_controller/) to see the full code

## [Demo video:](#demo-video)

[Youtube](https://www.youtube.com/watch?v=TDM_PmOblQE&list=PLowdHiSvu5G5llfsoOCy_r1utdYsJONEA)

## [References:](#references)

[1] [Harada, Kensuke, et al. "An analytical method for real-time gait planning for humanoid robots." International Journal of Humanoid Robotics 3.01 (2006): 1-19.](https://www.worldscientific.com/doi/abs/10.1142/S0219843606000643)

[2] [Eko Rudiawan](https://github.com/ekorudiawan)
