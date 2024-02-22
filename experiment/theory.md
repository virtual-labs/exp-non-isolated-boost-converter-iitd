### Theory

<center>
  <img src="images/th1.jpg" height="350px">
  
Fig. 1 Circuit diagram of boost converter.

</center>
<br>
Based on the modes of operation, the voltage gain formulation (in brief) is given below:
<br><br>

<center>
  
**Mode – I :  Switch S:ON-state, Diode: OFF-state**

<br>
<img src="images/th2.jpg" height="350px">
<br>

Fig. 1(a). Equivalent circuit in mode-I.
<br><br>

**Mode – II :  Switch S:OFF-state , Diode: ON-state**
<br>

<img src="images/th3.jpg" height="350px">
<br>
Fig. 1(b). Equivalent circuit in mode-II.
<br><br>

</center>

Voltage across inductor L: &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <img src="images/th4.png" height="25px"> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <img src="images/th5.png" height="25px">

<br><br>
Applying volt-sec balance on inductor: &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <img src="images/th6.png" height="25px">
<br><br>
Simplifying the expression &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <img src="images/th7.png" height="65px">

<center>
  
<img src="images/th8.jpg" height="350px">

Fig. 2.  Circuit configuration of boost converter with non-idealities.

</center>

Voltage across inductor L: &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <img src="images/th9.png" height="25px"> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <img src="images/th10.png" height="25px">

Applying volt-sec balance on inductor: &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <img src="images/th11.png" height="25px">

Simplifying the expression &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <img src="images/th12.png" height="100px">

In the event of battery voltage/load fluctuations, load voltage varies. However, DC-loads require constant voltage for their feasible/efficient operation, which demands automatic control. A simple PI-controller (proportional plus integral controller [2], see Fig. 4(a)) is capable of maintaining a constant load voltage despite  the fluctuations (battery voltage/load). Here, the controller adjusts the pulse width of the PWM signal [2] according to the input error signal. As shown in Fig. 4(b), the error signal is the difference between the reference voltage and actual load voltage.

<center>
  
<img src="images/th13.png" height="250px">

Fig. 3.  Block Diagram of closed-loop control.

</center>
<br><br><br>
<center>

Fig. 3.  Block Diagram of closed-loop control.
  
<img src="images/th14.png" height="500px">

</center>
