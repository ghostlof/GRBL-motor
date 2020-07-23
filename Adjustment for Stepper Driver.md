# Current Limit (Reference Voltage) Adjustment for Stepper Driver
A4988 sold by Zyltech, Rs=0.1 ohm. Thus the max current is Vref/0.4

Vref (Reference Voltage) is measured using a voltmeter between the ground of power supply and VDD of A4988 shield :
![measure](https://github.com/ghostlof/GRBL-motor/blob/master/Images/A4988.PNG)  
![measure 2](https://github.com/ghostlof/GRBL-motor/blob/master/Images/Vref.PNG)  

Vref = Imax /2 ;  
Imax is the maximal current __for one phase only__.  
Reference voltage is adjusted with a small screwdriver at the point indicated with the white arrow in the picture to the right. We suggest adjusting the reference voltage in small increments - no more than a quarter turn at a time.  
For our motor Imax is 2.8A/phase so Vref = 1.4V .  

# Reference
http://www.zyltech.com/arduino-cnc-shield-instructions/
