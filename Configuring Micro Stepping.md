# Configuring Micro Stepping for Each Axis
In the tables below high indicates that a jumper is inserted and low indicates that no jumper is inserted.  
For A4988 driver configuration :
  
|      MSO      |       MS1       |      MS2      | Microstep Resolution |
| ------------- | --------------- | --------------| ---------------------|
|       LOW     |       LOW       |       LOW     |       Full step      |
|      HIGH     |       LOW       |       LOW     |       Half step      |
|       LOW     |      HIGH       |       LOW     |     Quarter step     |
|      HIGH     |      HIGH       |       LOW     |      Eighth step     |
|      HIGH     |      HIGH       |      HIGH     |    Sixteenth step    |  

![position](https://github.com/ghostlof/GRBL-motor/blob/master/Images/config.PNG)  

# Reference
http://www.zyltech.com/arduino-cnc-shield-instructions/
