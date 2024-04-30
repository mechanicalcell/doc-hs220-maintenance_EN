# 1.10.5. Restriction of the Operation Area

When applying a robot, if you judge that a certain operation of the robot is not necessary, the robot operation area can be limited to secure a sufficient safety area. When there is collision between the robot with an external safety system such as a safety fence, this function will minimize damage. The operation range of axes 1, 2 and 3 of the robot is controlled by mechanical stoppers or electrical limit switches. If the operation range is changed by a mechanical stopper or electrical limit switch, the operation range limit parameter should be also changed in software. If necessary, the movement of three wrist axes can also be restricted. The limits of the operation area of each axis can be changed by the user. At the time of shipment, the robot is set to the maximum operation range. 

<style type="text/css">
    .block {background-color:#f8f8be}
</style>
<blockquote class="block">
    <ol style="list-style-type:disc" start="1">
        <br>
		<li>
            <font size = 3><b>Manual mode: Maximum speed is 250 mm/s </b></font><br>
            In manual mode, it is made possible that the worker can enter the safety area of the robot by the operator's own choice. 

   </li><br>
		<li>
            <font size = 3><b>Auto mode: The robot can be operated with a remote operation system.</b></font><br>
            Safety systems such as an entrance gate and a safety mat will be operating.<br>
            No one should be allowed to enter the area of the safety systems of the robot.
          </li><br>
    </ol>
</blockquote>