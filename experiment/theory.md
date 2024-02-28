### Theory

The circuit configuration of boost converter is given in Fig. 1

<center>
  <img src="images/th1.jpg" height="350px">
  
Fig. 1 Circuit configuration of Boost Converter.

</center>
<br>
Based on the operation of switch (Sw: ON/OFF-state) the operating principle of the converter is explained below briefly. 
<br><br>

<table border="0" align="center" style="width:100%; border:none;">
  <tr>
<td style="width:50%">
<center>
  
**Mode – I :  Switch (Sw): ON and Diode (Di): OFF**
<br>
<img src="images/th2.jpg">
<br><br>
Fig. 2(a). Equivalent circuit in mode-I.
<br><br>
</center>
</td>
<td style="width:50%">
  
<center>
  
**Mode – II :  Switch (Sw): OFF and Diode (Di): ON**
<br>
<img src="images/th3.jpg">
<br><br>
Fig. 2(b). Equivalent circuit in mode-II.
<br><br>
</center> 
    </td>
  </tr>
</table>
<br>

**a) Voltage conversion ratio or voltage gain (M)**

Voltage across inductor L:

**Mode – I :**
<br>
<div style="float: left; width:50%;">
  <img src="images/th4.png" height="25px">
      </div>
<div style="float: right; width:50%; text-align:center;">
    ..(1)
      </div>
<br><br>

**Mode – II :**
<br>
<div style="float: left; width:50%;">
  <img src="images/th5.png" height="25px">
      </div>
<div style="float: right; width:50%; text-align:center;">
    ..(2)
      </div>     
<br><br>

Applying volt-sec balance on inductor (eqn. 1 and 2)
<br>

<div style="float: left; width:50%;">
  <img src="images/th6.png" height="25px">
      </div>
<div style="float: right; width:50%; text-align:center;">
    ..(3)

</div>

<br><br>
On simplifying the eqn. 3
<br>

<div style="float: left; width:50%;">
  <img src="images/th7.png" height="60px">
      </div>
<div style="float: right; width:50%; text-align:center;" height="60px">
    ..(4)
  <br>
      </div>
<br>
<div style="float: left; width:100%;"><br>
  
**b) Effect of non-idealities on voltage gain expression:**
</div>

Current through capacitor

**Mode – I :**
<br>
<div style="float: left; width:50%;">
  <img src="images/th8.png" height="30px">
      </div>
<div style="float: right; width:50%; text-align:center;">
    ..(5)
      </div>
<br><br>

**Mode – II :**
<br>
<div style="float: left; width:50%;">
  <img src="images/th9.png" height="30px">
      </div>
<div style="float: right; width:50%; text-align:center;">
    ..(6)
      </div>
<br><br>      

Applying charge-sec balance on capacitor (eqn. 5 and 6)
<br>

<div style="float: left; width:50%;">
  <img src="images/th10.png" height="60px">
      </div>
<div style="float: right; width:50%; text-align:center;">
    ..(7)
      </div>
<br>
<div style="float: left; width:100%;">
  
On solving eqn. 7
</div>

<br>
<div style="float: left; width:50%;">
  <img src="images/th11.png" height="30px">
      </div>
<div style="float: right; width:50%; text-align:center;">
    ..(8)
      </div>
<br>
<div style="float: left; width:100%;"><br>

**c) Power balance under ideal condition (neglecting losses):**

From Fig. 1, the source current itself is the inductor current and hence

</div>

Current through capacitor

**Mode – I :**
<br>
<div style="float: left; width:50%;">
  <img src="images/th12.png" height="30px">
      </div>
<div style="float: right; width:50%; text-align:center;">
    ..(9)
      </div>
<br><br>

**Mode – II :**
<br>
<div style="float: left; width:50%;">
  <img src="images/th13.png" height="30px">
      </div>
<div style="float: right; width:50%; text-align:center;">
    ..(10)
      </div>
<br><br>      

Applying charge-sec balance on capacitor (eqn. 5 and 6)
<br>

<div style="float: left; width:50%;">
  <img src="images/th14.png" height="60px">
      </div>
<div style="float: right; width:50%; text-align:center;">
    ..(11)
      </div>
<br>
<div style="float: left; width:100%;">
  
On solving eqn. 11
</div>

<br>
<div style="float: left; width:50%;">
  <img src="images/th15.png" height="30px">
      </div>
<div style="float: right; width:50%; text-align:center;">
    ..(12)
      </div>
<br>
<div style="float: left; width:100%;"><br>

**d) Inductor current ripple:**     

From eqn. 1,

</div>


Current through capacitor

**Mode – I :**
<br>
<div style="float: left; width:50%;">
  <img src="images/th16.png" height="30px">
      </div>
<div style="float: right; width:50%; text-align:center;">
    ..(13)
      </div>
<br><br>

**Mode – II :**
<br>
<div style="float: left; width:50%;">
  <img src="images/th17.png" height="30px">
      </div>
<div style="float: right; width:50%; text-align:center;">
    ..(14)
      </div>
<br><br>      

<div style="float: left; width:100%;">
  
On solving eqn. 7
</div>

<br>
<div style="float: left; width:100%;"><br>

**c) Power balance under ideal condition (neglecting losses):**

From Fig. 1, the source current itself is the inductor current and hence

</div>


<br><br>==================================<br><br>
<div style="float: left; width:100%;">
<br>
In the event of battery voltage/load fluctuations, load voltage varies. However, DC-loads require constant voltage for their feasible/efficient operation, which demands automatic control. A simple PI-controller (proportional plus integral controller [2], see Fig. 5(a)) is capable of maintaining a constant load voltage despite the fluctuations (battery voltage/load). Here, the controller adjusts the pulse width of the PWM signal [2] according to the input error signal. As shown in Fig. 5(b), the error signal is the difference between the reference voltage and actual load voltage.
</div>

<br>

<center>
  
<img src="images/th14.png" height="500px">

</center>
