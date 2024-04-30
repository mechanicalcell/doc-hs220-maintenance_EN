# 1.5. Definition of Safety Functions

![](../_assets/말머리이미지.png )<font size = 3> **Emergency Stop Function - IEC 204-1,10,7** </font><br>
There is one emergency stop button on the controller and teach pendant respectively. If necessary, additional emergency buttons can be connected to the safety chain circuit of the robot. The emergency stop function is applied with priority over all other control functions of the robot. It can bring the current operation to a halt by cutting off the power supply to the motors of individual axes. This function will also shut down the power supply to prevent other dangerous functions that are controlled by the robot from being used.

![](../_assets/말머리이미지.png )<font size = 3> **Safety Stop - EN ISO 10218-1:2011** </font><br>
A safety stop circuit needs to be configured, and, through this circuit, each robot should be connected with the safety systems and interlocks. The robot should have a number of electric input signals which can be used to connect external safety devices, such as safety doors, safety pads, and safety lights. These signals allow the robot itself and peripheral facilities to perform safety functions for the robot. 

![](../_assets/말머리이미지.png )<font size = 3> **Speed Limit - EN ISO 10218-1:2011** </font><br>
In manual mode, the robot speed is limited to a maximum of 250 mm/s. The speed limit is applied not only to the Tool Center Point (TCP) but also to all robot’s parts that are to be manually operated. In addition, it should be made possible to monitor the speed of the equipment mounted on the robot.

![](../_assets/말머리이미지.png )<font size = 3> **Restriction of the Operation Area - ANSI/NFPA 79:2021** </font><br>
The operation area of each axis is restricted by the soft limit. In addition, the soft limit function also makes it possible to limit the operation areas of axes 1, 2, and 3 with mechanical stoppers.

![](../_assets/말머리이미지.png )<font size = 3> **Selection of the Operation Mode - ANSI/NFPA 79:2021** </font><br>
The robot can be operated in manual mode or in auto mode. In manual mode, the robot can be operated only by using the teach pendant.