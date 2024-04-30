# 3.6.1. Calculating the Allowable Load Torque

The load to be attached to the tip of the wrist axis of the robot is regulated by the allowable weight, allowable load torque, and allowable moment of inertia. The direction of the coordinate system to be used for calculating the load torque and moment of inertia is the same as that of the robot base coordinate system. The review of the R2 axis will be performed in the same way as done for the B axis.

*	Step 1

    Calculate the position of the center of gravity at the center of rotation of the B axis (L<sub>X</sub>, L<sub>Y</sub>, L<sub>Z</sub>.)

    L<sub>x</sub>: Position of the center of gravity in the direction of X axis

    L<sub>y</sub>: Position of the center of gravity in the direction of Y axis

    L<sub>z</sub>: Position of the center of gravity in the direction of Z axis



*	Step 2

    Calculate the distance from the B and R1 axes to the center of gravity respectively.

    ![](../../_assets/3.6.1_수식1.PNG)

    L<sub>B</sub> : Distance from the center of rotation of B axis to the center of gravity

    L<sub>R1</sub> : Distance from the center of rotation of the R1 axis to the center of gravity

*	Step 3

    Calculate the load torque based on the calculated distance.

    ![](../../_assets/3.6.1_수식2.PNG)

*	Step 4

    Check whether the load torque calculated in Step 3 is below the limit value based on the table of allowable load torques.

 
* Note: If the load mass is similar to the mass indicated on the torque curve below, the verification of the load torque can be substituted by checking whether the distance calculated in Step 2 is distributed within the torque curve instead of going through Steps 3 and 4. If the calculated distance is within the torque curve, the calculated load torque is smaller than the allowable load torque, and if it is located outside the torque curve, the calculated load torque is larger than the allowable load torque.


![](../../_assets/그림_3.13_손목축_토크_선도.png  )

Figure 3.10 Wrist Axis Torque Curve

<br></br>

![](../../_assets/작은주의표시.png) <b>Allowable Load Torque</b>

Table 3-1 Allowable Load Torque

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-zegx{background-color:#f8f8be;text-align:center;vertical-align:middle}
.tg .tg-nrix{text-align:center;vertical-align:middle}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-zegx" rowspan="2">Payload</th>
    <th class="tg-zegx" colspan="3">Allowable Load Torque</th>
  </tr>
  <tr>
    <th class="tg-zegx">Rotation of the R2 axis</th>
    <th class="tg-zegx">Rotation of the B axis</th>
    <th class="tg-zegx">Rotation of the R1 axis</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-nrix">HS160L,HS180</td>
    <td class="tg-nrix" colspan="2">Within 1079 N·m (110 kgf·m)</td>
    <td class="tg-nrix">Within 566 N·m (58 kgf·m)</td>
  </tr>
  <tr>
    <td class="tg-nrix">HS220</td>
    <td class="tg-nrix" colspan="2">Within 1422 N·m (145kgf·m)</td>
    <td class="tg-nrix">Within 770 N·m (79 kgf·m)</td>
  </tr>
</tbody>
</table>