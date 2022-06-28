<h1>Modelling and Control of a Quadrotor Helicopter</h1>


<h2>Description</h2>
This repository consist of detailed processes involved in the design and simulation of the mathematical model and control systems for a quadrotor helicopter via the use of extensive dynamic modeling; and control system error correction techniques using the proportional, integral, and derivative (PID) controller.
Furthermore, the quadrotor helicopter is an underactuated system where by six-degrees-of-freedom (i.e the earth's inertia variables <B>"X", "Y", "Z"</B>; and the quadrotor body rotational variables <B>"Theta", "Phi"</B>, and <B>"Psi"</B>) is controlled from four input signals (the four rotor voltages or angular speeds depending on the perspective of the analysis). Each of these input and output variables are design in subsystems and combined afterwards in a complete mathematical model for the quadrotor helicopter. More so, the control system for this model is then designed using the proportional, integral, and derivative controller coupled with a motor mixer to the complete quadrotor helicopter model for ease of maneuver.
These subsystems and the completed model are as shown in subsequent sections.
<br />


<h2>Languages and Utilities Used</h2>

- <b>MATLAB Simulink</b> 

<h2>Environments Used </h2>

- <b>Windows 10</b>

<h2>Program walk-through:</h2>

<p align="center">
<B>Derived Equation for the Actuator Subsystem </B><br/>
<img src="https://i.imgur.com/l7FwAM6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<B>Mathematical Modelling of Actuator equation on MATLAB Simulink</B><br/>
<img src="https://i.imgur.com/FNCPprD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<B>Derived Roll Subsystem Equation</B><br/>
<img src="https://i.imgur.com/3S1Vqob.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<B>Mathematical Modelling of the Roll Subsystem Equation on MATLAB Simulink</B><br/>
<img src="https://i.imgur.com/zkbeI26.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<B>Derived Pitch Subsystem Equation</B><br/>
<img src="https://i.imgur.com/x5G3hSt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<B>Mathematical Modelling of the Pitch Subsystem Equation on MATLAB Simulink</B><br/>
<img src="https://i.imgur.com/7z1TCyc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<B>Derived Yaw Subsystem Equation </B><br/>
<img src="https://i.imgur.com/31abhQr.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<B>Mathematical Modelling of the Yaw Subsystem Equation on MATLAB Simulink</B><br/>
<img src="https://i.imgur.com/WCZzvxx.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
