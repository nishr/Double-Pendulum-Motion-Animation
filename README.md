# Double-Pendulum-Motion-Animation
<p float="left">
<a href = "https://github.com/zaman13/Double-Pendulum-Motion-Animation/tree/master/Julia%20Code"> <img src="https://img.shields.io/badge/Language-Julia-blue" alt="alt text"> </a>
<a href = "https://github.com/zaman13/Double-Pendulum-Motion-Animation/tree/master/Python%20Code"> <img src="https://img.shields.io/badge/Language-Python-blue" alt="alt text"> </a>
<a href = "https://github.com/zaman13/Double-Pendulum-Motion-Animation/blob/master/LICENSE"> <img src="https://img.shields.io/badge/license-MIT-green" alt="alt text"></a>
<a href = "https://github.com/zaman13/Double-Pendulum-Motion-Animation"> <img src="https://img.shields.io/badge/version-1.1-red" alt="alt text"> </a>
</p>
Animation of the chaotic motion a double-pendulum using Julia and Python.

## Julia version <a href = "https://github.com/zaman13/Double-Pendulum-Motion-Animation/tree/master/Julia%20Code"> <img src="https://img.shields.io/badge/Language-Julia-blue" alt="alt text"> </a>
The code can save the animation as a gif file. It can also playback the video in Jupyter notebook environment. The animation is recorded at equal time steps to preserve relative velocity of the pendulums in the video.

## Python version <a href = "https://github.com/zaman13/Double-Pendulum-Motion-Animation/tree/master/Python%20Code"> <img src="https://img.shields.io/badge/Language-Python-blue" alt="alt text"> </a>
The animation is done using FuncAnimation() of matplotlib. The code can save the animation as a mp4 file. The python script was tested in spyder environment. Plotting in external window should be enabled to view the animation.



## Package requirements for Julia version
 1. Plots
 2. Differential Equations
 3. Direckx

## Package requirements for Python version
 1. numpy
 2. scipy.integrate (odeint)
 3. pylab, matplotlib (animation) 


## Use
The mass and length of the pendulums, gravitational acceleration constant, the initial conditions and the simulaiton duration are defined at the beginning of the code. Different cases can be simulated by changing these parameters. 




## Sample output
Double pendulum system with m<sub>1</sub> = m<sub>2</sub> = 1kg, L<sub>1</sub> = L<sub>2</sub> = 1m. Initial conditions θ<sub>1</sub> = 5π/8, θ<sub>2</sub> = 5π/9, ω<sub>1</sub> = 0, ω<sub>2</sub> = 0. Here, θ<sub>1</sub> and θ<sub>2</sub> are the initial angular positions, and, ω<sub>1</sub> and ω<sub>2</sub> are initial angular velocities in SI units.


<img src="https://github.com/zaman13/Double-Pendulum-Motion-Animation/blob/master/sample_output.gif" alt="alt text" width="300">



## References
1. http://sophia.dtp.fmph.uniba.sk/~kovacik/doublePendulum.pdf
2. http://www.phys.lsu.edu/faculty/gonzalez/Teaching/Phys7221/DoublePendulum.pdf

