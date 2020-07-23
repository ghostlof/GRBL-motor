# Configuring Micro Stepping for Each Axis
In the tables below high indicates that a jumper is inserted and low indicates that no jumper is inserted.  
For A4988 driver configuration :
  
|      MSO      |       MS1       |      MS2      | Microstep Resolution |
| ------------- | --------------- | --------------| ---------------------|
|       LOW     |       LOW       |       LOW     |       Full step      |
|      HIGHT    |       LOW       |       LOW     |       Half step      |
|       LOW     |      HIGHT      |       LOW     |     Quarter step     |
|      HIGHT    |      HIGHT      |       LOW     |      Eighth step     |
|      HIGHT    |      HIGHT      |      HIGHT    |    Sixteenth step    |  

![position](https://github.com/ghostlof/GRBL-motor/blob/master/Images/config.PNG)  

# Reference
http://www.zyltech.com/arduino-cnc-shield-instructions/
