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
<img src="images/th3.jpg">
<br><br>
Fig. 2(a). Equivalent circuit in mode-I.
<br><br>
</center>
</td>
<td style="width:50%">
  
<center>
  
**Mode – II :  Switch (Sw): OFF and Diode (Di): ON**
<br>
<img src="images/th2.jpg">
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
  
**b) Average current through inductor (I<sub>L</sub>):**
<br>
Current through capacitor

**Mode – I :**
</div>
<br><br>

<div style="float: left; width:50%;">
  <img src="images/th8.png" height="30px">
      </div>
<div style="float: right; width:50%; text-align:center;">
    ..(5)
      </div>
<br><br>

<div style="float: left; width:100%;"><br>
  
  **Mode – II :**
<br></div>

<div style="float: left; width:50%;">
  <img src="images/th9.png" height="30px">
      </div>
<div style="float: right; width:50%; text-align:center;">
    ..(6)
      </div>
<br><br>

<div style="float: left; width:100%;"><br>
Applying charge-sec balance on capacitor (eqn. 5 and 6)
<br><br>
</div>

<div style="float: left; width:50%;">
  <img src="images/th10.png" height="30px">
      </div>
<div style="float: right; width:50%; text-align:center;">
    ..(7)
      </div>

<div style="float: left; width:100%;"><br><br>
On solving eqn. 7
<br><br>
</div>


<div style="float: left; width:50%;">
  <img src="images/th11.png" height="60px">
      </div>
<div style="float: right; width:50%; text-align:center;">
    ..(8)
      </div>
<br>
<div style="float: left; width:100%;"><br>

**c) Power balance under ideal condition (neglecting losses):**
<br><br>
From Fig. 1, the source current itself is the inductor current and hence
<br>
</div>

<br>
<div style="float: left; width:50%;">
  <img src="images/th12.png" height="30px">
      </div>
<div style="float: right; width:50%; text-align:center;">
    ..(9)
      </div>
      
<div style="float: left; width:100%;"><br><br>
Simplifying eqns. 8 and 9 gives the current gain
<br><br>
</div>

<div style="float: left; width:50%;">
  <img src="images/th13.png" height="60px">
      </div>
<div style="float: right; width:50%; text-align:center;">
    ..(10)
      </div>    

<div style="float: left; width:100%;"><br><br> 
From eqns. 4 and 10
<br><br> 
</div>

<div style="float: left; width:50%;">
  <img src="images/th14.png" height="60px">
      </div>
<div style="float: right; width:50%; text-align:center;">
    ..(11)
      </div>

<div style="float: left; width:100%;">
<br><br>   
Hence under ideal condition, the power drawn from the source is equal to power supplied to load.
</div>

<br><br>
<div style="float: left; width:50%;">
  <img src="images/th15.png" height="32px">
      </div>
<div style="float: right; width:50%; text-align:center;">
    ..(12)
      </div>
<br>
<div style="float: left; width:100%;"><br>

**d) Inductor current ripple:**     

From eqn. 1,
</div>

<br>
<div style="float: left; width:50%;">
  <img src="images/th16.png" height="60px">
      </div>
<div style="float: right; width:50%; text-align:center;">
    ..(13)
      </div>
<br><br>

<div style="float: left; width:100%;">
  
Therefore, the inductor ripple current is    
</div>

<div style="float: left; width:50%;">
  <img src="images/th17.png" height="60px">
      </div>
<div style="float: right; width:50%; text-align:center;">
    ..(14)
      </div>
<br><br>      

<br>
<div style="float: left; width:100%;"><br>

**e) Current through various components:**

The current through various components are given in Fig. 3.

</div>

<center>
  <img src="images/th18.png">
  
Fig. 3. Current through various components.

</center>
<br>
<center>
<table align="center" width="100%" >
  <tr style="text-align: center; font-weight: bold; background-color: #c9c9c9;">
    <td style="text-align: center; font-weight: bold;">&nbsp;</td>
    <td style="text-align: center; font-weight: bold;" colspan="2">
      Mode-I<br>(DT)
    </td>
    <td style="text-align: center; font-weight: bold;" colspan="2">
      Mode-II<br>(1-D)T
    </td>
    <td style="text-align: center; font-weight: bold;">Average Current</td>
  </tr>
  <tr style="background-color: #c9c9c9;">
    <td></td>
    <td>i<sub>min</sub></td>
    <td>i<sub>max</sub></td>
    <td>i<sub>min</sub></td>
    <td>i<sub>max</sub></td>
    <td>I<sub>avg</sub></td>
  </tr>
  <tr style="background-color: #FFF;">
    <td>i<sub>L</sub></td>
    <td><img src="images/th19.png" height="60px"></td>
    <td><img src="images/th20.png" height="60px"></td>
    <td><img src="images/th21.png" height="60px"></td>
    <td><img src="images/th22.png" height="60px"></td>
    <td><img src="images/th23a.png" height="35px"></td>
  </tr>
  <tr style="background-color: #FFF;">
    <td>i<sub>C</sub></td>
    <td><img src="images/th23b.png" height="35px"></td>
    <td><img src="images/th23c.png" height="35px"></td>
    <td><img src="images/th23.png" height="60px"></td>
    <td><img src="images/th24.png" height="60px"></td>
    <td>&#48;</td>
  </tr>
  <tr style="background-color: #FFF;">
    <td>i<sub>Sw</sub></td>
    <td><img src="images/th25.png" height="60px"></td>
    <td><img src="images/th26.png" height="60px"></td>
    <td>&#48;</td>
    <td>&#48;</td>
    <td><img src="images/th27.png" height="60px"></td>
  </tr>
  <tr style="background-color: #FFF;">
    <td>i<sub>Di</sub></td>
    <td>&#48;</td>
    <td>&#48;</td>
    <td><img src="images/th28.png" height="60px"></td>
    <td><img src="images/th29.png" height="60px"></td>
    <td><img src="images/th30.png" height="60px"></td>
  </tr>
</table>
</center>
<br>

<div style="float: left; width:100%;"><br>

**f) Voltage and current stress on various components:**

</div>
<br>
<center>		
<table align="center" style="width: 100%;">
  <tr style="text-align: center; font-weight: bold; background-color: #c9c9c9;">
    <td style="text-align: center; font-weight: bold;">
      Component
    </td>
    <td style="text-align: center; font-weight: bold;">
      Voltage stress
    </td>
    <td style="text-align: center; font-weight: bold;">
      Current Stress
    </td>
  </tr>
  <tr style="background-color: #FFF;">
    <td>Inductor (L)</td>
    <td><img src="images/th31.png" height="60px"></td>
    <td><img src="images/th32.png" height="60px"></td>
  </tr>
  <tr style="background-color: #FFF;">
    <td>Capacitor (C)</td>
    <td><em>V<sub>&#48;</sub></em></td>
    <td><img src="images/th33.png" height="60px"></td>
  </tr>
  <tr style="background-color: #FFF;">
    <td>Switch (Sw)</td>
    <td><em>V<sub>&#48;</sub></em></td>
    <td><img src="images/th34.png" height="60px"></td>
  </tr>
  <tr style="background-color: #FFF;">
    <td>Diode (Di)</td>
    <td><em>V<sub>&#48;</sub></em></td>
    <td><img src="images/th35.png" height="60px"></td>
  </tr>
</table>

</center>

<br>
<div style="float: left; width:100%;"><br>

**g) Efficiency analysis:**     

</div>

<br>
<div style="float: left; width:50%;">
  <img src="images/th36.png" height="70px">
      </div>
<div style="float: right; width:50%; text-align:center;">
    ..(15)
      </div>

<div style="float: left; width:100%;">
<br><br>    
</div>

<div style="float: left; width:50%;">
  <img src="images/th37.png" height="80px">
      </div>
<div style="float: right; width:50%; text-align:center;">
    ..(16)
      </div>

<div style="float: left; width:100%;"><br><br>
     
The power loss occurring in various components are given below.<br><br>
Power loss in inductor:
</div>

<br>
<div style="float: left; width:50%;">
  <img src="images/th38.png" height="60px">
      </div>
<div style="float: right; width:50%; text-align:center;">
    ..(17)
      </div>
<br><br>

<div style="float: left; width:100%;">
  
Power loss in capacitor:    
</div>

<div style="float: left; width:50%;">
  <img src="images/th39.png" height="60px">
      </div>
<div style="float: right; width:50%; text-align:center;">
    ..(18)
      </div>

<div style="float: left; width:100%;"><br>

Power loss in switch:
</div>

<br>
<div style="float: left; width:50%;">
  <img src="images/th40.png" height="60px">
      </div>
<div style="float: right; width:50%; text-align:center;">
    ..(19)
      </div>
<br><br>

<div style="float: left; width:100%;">
  
Power loss in Diode:   
</div>

<div style="float: left; width:50%;">
  <img src="images/th41.png" height="60px">
      </div>
<div style="float: right; width:50%; text-align:center;">
    ..(20)
      </div>

<div style="float: left; width:100%;"><br>
     
Total power loss:
</div>

<br>
<div style="float: left; width:50%;">
  <img src="images/th42.png" height="60px">
      </div>
<div style="float: right; width:50%; text-align:center;">
    ..(21)
      </div>
<br><br>

<br>
<div style="float: left; width:100%;"><br>

**h) Effect of non-idealities on voltage gain expression:**     

</div>

<br><br>

<center>
  <img src="images/th43.png" height="350px">
  
Fig. 4.  Circuit configuration of conventional boost converter with non-idealities.

</center>
<br>
Based on the operation of switch (Sw: ON/OFF-state) the operating principle of the converter is explained below briefly. 
<br><br>

<div style="float: left; width:100%;"><br><br>

Voltage across inductor L<br>

**Mode – I :**
</div>

<br>
<div style="float: left; width:50%;">
  <img src="images/th44.png" height="60px">
</div>
<div style="float: right; width:50%; text-align:center;">
    ..(22)
</div>
<br><br>
<div style="float: left; width:100%;">
     
**Mode – II :**
</div>

<br>
<div style="float: left; width:50%;">
  <img src="images/th45.png" height="60px">
      </div>
<div style="float: right; width:50%; text-align:center;">
    ..(23)
      </div>     


<div style="float: left; width:100%;"><br><br>
  
Applying volt-sec balance on inductor (eqn. 22 and 23) <br><br>  
</div>

<div style="float: left; width:50%;">
  <img src="images/th46.png" >
      </div>
<div style="float: right; width:50%; text-align:center;">
    ..(24)
      </div>

<div style="float: left; width:100%;"><br>
     
Therefore, voltage gain of non-ideal boost converter is
</div>


<div style="float: left; width:50%;"><br>
  <img src="images/th47.png" height="210px">
      </div>
<div style="float: right; width:50%; text-align:center;">
    ..(25)
      </div>
<br><br>

