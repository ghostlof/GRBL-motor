# Jumper Settings
Jumpers are used to configure the 4th Axis, Micro stepping and endstop configuration.

# 4th Axis Configuration
Using two jumpers the 4th axis can be configured to clone the X or Y or Z axis. It can also run as an individual axis by using Digital Pin 12 for Stepping signal and Digital Pin 13 as direction signal. (GRBL only supports 3 axis’s at the moment).  
__Warning : If you do this step be sure to did it well because it can damage your system. In case of doubt don't do it and do the stepper configuration separetly for each stepper motor.__  

![X](https://github.com/ghostlof/GRBL-motor/blob/master/Images/clone%20X.PNG)  
Clone X-axis to the 4th stepper driver (marked as A)  

![Y](https://github.com/ghostlof/GRBL-motor/blob/master/Images/clone%20Y.PNG)  
Clone Y-axis to the 4th stepper driver (marked as A)  

![Z](https://github.com/ghostlof/GRBL-motor/blob/master/Images/clone%20Z.PNG)  
Clone Z-axis to the 4th stepper driver (marked as A)  

![A](https://github.com/ghostlof/GRBL-motor/blob/master/Images/clone%204.PNG)  
Use D12 and D13 to drive the 4th stepper driver (marked as A)  
