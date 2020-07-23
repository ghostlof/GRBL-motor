# Current Limit (Reference Voltage) Adjustment for Stepper Driver

Vref (Reference Voltage) is measured using a voltmeter between the ground of power supply and VDD of A4988 shield :  
![measure](https://github.com/ghostlof/GRBL-motor/blob/master/Images/A4988.PNG)  
![measure 2](https://github.com/ghostlof/GRBL-motor/blob/master/Images/Vref.PNG)  

Rsense : resistor value present on the PCB, they are often screenprinted "S1, S2, S1X, S2X, R1, R2…" , and may be 0.05 ohm (Marking R050), 0.1 ohm (R100) or 0.2 ohm (R200).  
Inom = Imax/sqrt(2) ; Imax is the maximal current __for one phase only__.   


For A4988 driver:  
__Inom = Vref / (8 * Rsense) donc Vref = Inom * 8 * Rsense__  
(For DRV8825 driver : Inom = Vref / (5 * Rsense) donc Vref = Inom * 5 * Rsense)

 
Reference voltage is adjusted with a small screwdriver at the point indicated with the white arrow in the picture to the right. We suggest adjusting the reference voltage in small increments - no more than a quarter turn at a time.  
Example :  
For A4988 with Rsense = 0.05 ohm (screenprinted R050) ans with Imax = 1.8A ==> Inom = 1.27A ==> Vref = 1.27 * 8 * 0.05 = 0.51V.  


__NOTE : The maximum current per phase for an A4988 is 2A and 2.5A for the DRV8825. So if you are in the high limit of your drivers, reduce Imax a little.__  

![imax](https://github.com/ghostlof/GRBL-motor/blob/master/Images/Imax.PNG)

# Reference
http://www.zyltech.com/arduino-cnc-shield-instructions/
https://www.lesimprimantes3d.fr/forum/topic/10459-pi%C3%A8ges-des-r%C3%A9glages-vref-a4988-ou-drv8825/

