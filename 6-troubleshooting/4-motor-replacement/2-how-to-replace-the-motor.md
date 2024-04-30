# 6.4.2. How to Replace the Motor

<blockquote>
<table border="0">
<thead>
  <tr>
    <td>
    <div align="center">
      <img src="../../_assets/주의표시.png" width = 80 height = 80>
    </div>
    </td>
    <td colspan="4">This robot has a brake built into the motor to maintain the posture of the arm, so the arm will fall if the motor is removed. You must take safety measures such as hanging the arm using a crane and inserting fixing bolts to fix the first and second arms to prevent the falling.</td>
  </tr>
</thead>
</table>  
</blockquote>

<br> 

<ol style="list-style-type:decimal" start="1">
<li>
Set the controller to the teaching mode and set the Operation Ready function to the [ON] state. If it is impossible to set the Operation Ready function to the [ON] state, you should make sure that the arm does not fall and that the arm is sufficiently fixed. After that, you can perform the work starting from step (4.)
  </li><br>
    <li>
Put the axis that requires the replacement of the motor into the basic posture.
  </li><br>
    <li>
For the main axes (S, H, V): Refer to [Figures 6.1–6.4.] 
For H and V axes, insert the fixing bolts to prevent the arm from falling.
For the wrist axes (R2, B, and R1): Set the origin of each axis by using the scale.
  </li><br>
    <li>
Turn [OFF] the power of the controller and then turn [OFF] the primary power.
  </li><br>
    <li>
Separate the motor wirings.
  </li><br>
    <li>
Separate the motor from the manipulator by removing the motor attachment bolts.
When removing the motors of H and V axes, you should make sure that the lip of the oil seal is not damaged by the gear attached on the axis of the motor.
  </li><br>
    <li>
Separate the gear attached on the axis of the motor. 
At this time, take precautions not to allow a strong impact to be applied to the axis of the motor.
  </li><br>
    <li>
Apply a thin layer of grease to the axis of the motor to be assembled and assemble the gear.
At this time, the bolts to be used to fasten the gear to the axis of the motor should be cleaned and degreased and applied with anti-loosening bond (Loctite 243) to the screw and then tightened with the prescribed torque using a torque wrench. In addition, the bolts should be slowly tightened in the symmetrical order.
  </li><br>
    <li>
Apply a small amount of grease to the lip of the oil seal and an appropriate amount of grease to the tooth surface of the gear, and then assemble the motor to the manipulator. When attaching the motors of the main axes, you should make sure that the lip of the oil seal is not damaged by the gear attached to the axis of the motor.
  </li><br>
    <li>
Connect the wiring of the motor.
  </li><br>
    <li>
When the motors of the H and V axes are replaced, replenish new grease as much as the amount of leaked grease.
  </li><br>
    <li>
Reset the encoder of the axis for which the motor has been replaced.
<br>

<table>
<thead>
  <tr>
    <td>
    <div align="center">
      <img src="../../_assets/주의표시.png" width = 60 height = 60>
    </div>
    </td>
    <td colspan="4">Before calibrating the encoder, you should set the Operation Ready function to the [ON] state, and then press the Enable switch of the teach pendant for 2–3 seconds to check if the power is turned on.</td>
  </tr>
</thead>
</table>  
</li>
<li>
Calibrate the encoder of the axis for which the motor has been replaced by referring to the [Calibrating the Encoder] section in the Controller Operation Manual.
  </li><br>
    <li>
Disassemble the M20 bolts, which are designed for preventing the arms of H and V axes from falling.
  </li><br>
    <li>
Check whether there is any abnormality.
</li>
</ol>

<br>


![](../../_assets/그림_6.1_arm축_고정용_볼트_삽입_위치.png)

Figure 6.1 Position for Inserting the Fixing Bolt for the Primary Arm (H Axis)



![](../../_assets/그림_6.2_arm축_고정용_볼트_삽입_위치.png)

Figure 6.2 Position for Inserting the Fixing Bolt for the Secondary Arm (V Axis)


![](../../_assets/그림_6.3_s축모터.png)

Figure 6.3 S-Axis Motor Assembly

![](../../_assets/그림_6.4_h_v축모터.png)

Figure 6.4 H-Axis and V-Axis Motor Assemblies

<br>
<blockquote>
<table border="0">
<thead>
  <tr>
    <td><img src="../../_assets/주의표시.png" width = 60 height = 60> </td>
    <td colspan="4">When the V-axis motor is being replaced, if the entire upper arm is not accurately attached to the mechanical stopper in the direction of gravity, the upper arm may rotate while the motor is being separated.</td>
  </tr>
</thead>
</table>
</blockquote>


![](../../_assets/그림_6.5_손목축모터.png)

Figure 6.5 Wrist-Axis Motor Assembly