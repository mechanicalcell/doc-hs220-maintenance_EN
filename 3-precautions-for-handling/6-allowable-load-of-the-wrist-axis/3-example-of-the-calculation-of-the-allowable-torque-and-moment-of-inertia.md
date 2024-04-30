# 3.6.3. Examples of Calculation of the Allowable Torque and Allowable Moment of Inertia (HS180)

(1)	Case #1 Simple two-dimensional model

![](../../_assets/그림_3.14_2차원_부하_모델.png)

Figure 3.11 Two-Dimensional Load Model



M - Load weight 

J<sub>xx</sub> - Moment of inertia in the direction of the X axis at the center of the gravity of the load

J<sub>yy</sub> - Moment of inertia in the direction of the Y axis at the center of the gravity of the load

J<sub>zz</sub> - Moment of inertia in the direction of the Z axis at the center of the gravity of the load

J<sub>a4</sub> - Moment of inertia at the center of rotation of the R2 axis

J<sub>a5</sub> - Moment of inertia at the center of rotation of the B axis

J<sub>a6</sub> - Moment of inertia at the center of rotation of the R1 axis


 
<br></br>
☞ Load condition: Stainless Steel (with mass of 138.15 kg) with a width of 260 mm and a thickness of 260 mm

① Weight limit

Load weight: 138.15 ≤180 kg

<br>

② Limit of the allowable torque

The position of the center of gravity with respect to B axis L<sub>X</sub> = 350mm, L<sub>Y</sub> = 0mm, L<sub>Z</sub> = -60mm

Each distance from B axis and R1 axis to the center of gravity can be calculated respectively as follows.

![](../../_assets/3.6.3_수식1.png)

<br>

③ Limit of the allowable moment of inertia

The moments of inertia of the load at the center of gravity  J<sub>xx</sub>= 1.56kgm², J<sub>yy</sub>= 1.56 kgm², J<sub>zz</sub>= 1.56 kgm²
    
![](../../_assets/3.6.3_수식2.png)

<br>
  
④ Conclusion

It is safe because all conditions of weight, torque, and moment of inertia satisfy the conditions of limit.

<br></br>

(2)	Case #2 Complex three-dimensional model

![](../../_assets/그림_3.15_3차원_부하_모델_2D_형상.png)

Figure 3.12 Two-Dimensional Shape of a Three-Dimensional Load Model

<br></br>

Combination of aluminum block shapes
(σ=0.0027 g/mm<sup>3</sup> : 176.3 kg)

m1 (60 X 300 X 300)	 14.6kg

m2 (480 X 440 X 220)	125.4kg

m3 (280 X 300 X 160)	 36.3kg

<br>

mi  - Load weight of i block

L<sub>xi</sub> - - Position of the center of gravity of i block in the direction of X axis

L<sub>yi</sub> - - Position of the center of gravity of i block in the direction of Y axis

L<sub>zi</sub> - - Position of the center of gravity of i block in the direction of Z axis

<br>

① Weight limit

Load weight: 176.3 ≤180 kg

② Limit of the allowable torque

The position of the center of gravity of all loads at the center of rotation of the B axis can be calculated as follows.

![](../../_assets/3.6.3_수식3.png)


<br>

Position of the center of gravity of all blocks with respect to B axis L<sub>x</sub> = 520.85mm, L<sub>y</sub> = 0mm L<sub>z</sub> = -238.47mm

<br>

![](../../_assets/3.6.3_수식4.png)

<br>

x1 y1 z1 – Lengths of m1 block in the x, y, and z directions respectively

x2 y2 z2 – Lengths of m2 block in the x, y, and z directions respectively

x3 y3 z3 – Lengths of m3 block in the x, y, and z directions respectively

<br>

L<sub>X1</sub>, L<sub>Y1</sub>, L<sub>Z1</sub> - Position of the center of gravity of m1 block at the center of rotation of the B axis

L<sub>X2</sub>, L<sub>Y2</sub>, L<sub>Z2</sub> - BPosition of the center of gravity of m2 block at the center of rotation of the B axis

L<sub>X3</sub>, L<sub>Y3</sub>, L<sub>Z3</sub> - Position of the center of gravity of m3 block at the center of rotation of the B axis

<br>

J<sub>xx1</sub>, J<sub>yy1</sub>, J<sub>zz1</sub> – Moment of inertia of each of x, y, and z axes at the center of gravity of m1 block.

J<sub>xx2</sub>, J<sub>yy2</sub>, J<sub>zz2</sub> – Moment of inertia of each of x, y, and z axes at the center of gravity of m2 block.

J<sub>xx3</sub>, J<sub>yy3</sub>, J<sub>zz3</sub> – Moment of inertia of each of x, y, and z axes at the center of gravity of m3 block.


![](../../_assets/그림_3.16_3차원_부하_모델_3D_형상.png)


Figure 3.13 Three-Dimensional Shape of a Three-Dimensional Load Model


<br>

③ Limit of the allowable moment of inertia

Table 3-3 Moment of Inertia at the Center of Gravity of Each Block
<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-1e26{background-color:#f8f8be;color:#000000;font-weight:bold;text-align:center;vertical-align:top}
.tg .tg-baqh{text-align:center;vertical-align:top}
.tg .tg-amwm{font-weight:bold;text-align:center;vertical-align:top}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-1e26">Block weight (kg)</th>
    <th class="tg-1e26">Center of gravity (L<sub>X</sub>, L<sub>Y</sub>, L<sub>Z</sub>)</th>
    <th class="tg-1e26">J<sub>xx</sub></th>
    <th class="tg-1e26">J<sub>yy</sub></th>
    <th class="tg-1e26">J<sub>zz</sub></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-amwm">m<sub>1</sub>(14.6)</td>
    <td class="tg-baqh">(0.25, 0, 0)</td>
    <td class="tg-baqh">0.219 kgm²</td>
    <td class="tg-baqh">0.114 kgm²</td>
    <td class="tg-baqh">0.114 kgm²</td>
  </tr>
  <tr>
    <td class="tg-amwm">m<sub>2</sub>(125.4)</td>
    <td class="tg-baqh">(0.48, 0, -0.26)</td>
    <td class="tg-baqh">2.530 kgm²</td>
    <td class="tg-baqh">2.915 kgm²</td>
    <td class="tg-baqh">4.433 kgm²</td>
  </tr>
  <tr>
    <td class="tg-amwm">m<sub>3</sub>(36.3)</td>
    <td class="tg-baqh">(0.89, 0, -0.26)</td>
    <td class="tg-baqh">0.350 kgm²</td>
    <td class="tg-baqh">0.314 kgm²</td>
    <td class="tg-baqh">0.509 kgm²</td>
  </tr>
</tbody>
</table>


<br>

![](../../_assets/3.6.3_수식5.png)

<br>
④ Conclusion

It is safe because all conditions of weight, torque, and moment of inertia satisfy the conditions of limit. 



