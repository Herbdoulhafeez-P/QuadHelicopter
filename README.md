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

<h2>Mathematical Modelling of the Quadrotor Helicopter</h2>

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
<B>Derived X-Motion Subsystem Equation </B><br/>
<img src="https://i.imgur.com/Sg5deb7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<B>Mathematical Modelling of the X-Motion Subsystem Equation on MATLAB Simulink</B><br/>
<img src="https://i.imgur.com/uvsdjLy.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<B>Derived Y-Motion Subsystem Equation </B><br/>
<img src="https://i.imgur.com/l7p88YY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<B>Mathematical Modelling of the Y-Motion Subsystem Equation on MATLAB Simulink</B><br/>
<img src="https://i.imgur.com/0JNKYz4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<B>Derived Z-Motion Subsystem Equation </B><br/>
<img src="https://i.imgur.com/Vj5EWss.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<B>Mathematical Modelling of the Z-Motion Subsystem Equation on MATLAB Simulink</B><br/>
<img src="https://i.imgur.com/lf09r1x.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
 <B>The Complete Mathematical Model for the Quadrotor Helicopter</B><br/>
<img src="https://i.imgur.com/QzURoVU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
</p>
<h2>The Motor Mixer</h2>
The motor mixer is an intermediate subsystem deployed between the PID controller and the quadrotor. Its basic function is to provide an automatic control mechanism for the quadrotor actuator input voltages in order to achieve the required maneuvers (<B>"Throttle", "Pitch", "Roll"</B>, and <B>"Yaw"</B>) necessary to successfully fly the quadrotor.
</Br>
It should be noted that <B>32.159245</B> fed-forward in the Simulink model for the motor mixer shown below <B>is</B> the <B>calculated take-off voltage</B> which all the 4 rotors of the quadrotor must supply for the quadrotor <B>to offset gravity</B> by taking off from rest.
</Br>
</Br>
</Br>
<p align="center">
<B>The Quadrotor Motor Mixer</B><br/>
<img src="https://i.imgur.com/fcW494V.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
