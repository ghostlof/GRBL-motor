# GRBL-motor
# How to pilot stepper motor with GRBL librarie 

This repository contain all informations, driver and arduino librarie to pilot stepper motor.  
All document are available for [Arduino UNO](https://fr.rs-online.com/web/p/kits-de-developpement-pour-processeurs-et-microcontroleurs/7154081?cm_mmc=FR-PLA-DS3A-_-google-_-CSS_FR_FR_Semi-conducteurs_Whoop-_-(FR:Whoop!)+Kits+de+d%C3%A9veloppement+pour+processeurs+et+microcontr%C3%B4leurs-_-7154081&matchtype=&pla-339391921421&gclid=EAIaIQobChMIrqXv4uji6gIVy9vVCh1vcA0YEAQYASABEgIcsfD_BwE&gclsrc=aw.ds) 
and [Arduino MEGA](https://fr.rs-online.com/web/p/kits-de-developpement-pour-processeurs-et-microcontroleurs/7154084/) only.  
For beginner with stepper motor : [how does it work](https://www.monolithicpower.com/en/stepper-motors-basics-types-uses#:~:text=The%20basic%20working%20principle%20of,rotor%20aligns%20with%20this%20field.&text=When%20coil%20B%20is%20energized,with%20the%20new%20magnetic%20field.).  
In this repository explanations will be given for Arduino UNO. 

# For starters
### Equipment
* [Arduino UNO](https://fr.rs-online.com/web/p/kits-de-developpement-pour-processeurs-et-microcontroleurs/7154081?cm_mmc=FR-PLA-DS3A-_-google-_-CSS_FR_FR_Semi-conducteurs_Whoop-_-(FR:Whoop!)+Kits+de+d%C3%A9veloppement+pour+processeurs+et+microcontr%C3%B4leurs-_-7154081&matchtype=&pla-339391921421&gclid=EAIaIQobChMIrqXv4uji6gIVy9vVCh1vcA0YEAQYASABEgIcsfD_BwE&gclsrc=aw.ds),
* [Arduino transfer cable](https://fr.rs-online.com/web/p/products/4581654/),
* [CNC shield](https://www.amazon.fr/DollaTek-Engraver-Printer-dextension-Pilotage/dp/B07DK5CMMG/ref=sr_1_40?dchild=1&keywords=cnc+shield&qid=1595489807&sr=8-40),
* [Stepper driver A4988](https://www.amazon.fr/Longruner-A4988-Stepstick-dissipatore-stampante-confezione/dp/B071P41ZBW/ref=sr_1_5?dchild=1&keywords=driver+a4988&qid=1595490012&sr=8-5),
* [Stepper motor](https://www.amazon.fr/Couette-23-Moteur-1-26-Nm-conducteur-Imprimante/dp/B06XVC23Z7/ref=sr_1_5?dchild=1&keywords=Nema+23+Stepper+Motor&qid=1595316851&sr=8-5),
* Power supply : you can buy [that type](https://fr.rs-online.com/web/p/cordons-electriques/6563816/) and cut the end to seperate voltage and ground,
* [Short circuiting jumper](https://fr.rs-online.com/web/p/cavaliers-et-shunts/2518503/),
* [Microswitch](https://www.sparkfun.com/products/13119),
* Wire,
* [Arduino Iddle](https://www.arduino.cc/en/Main/Software)
* [GRBL librarie](https://github.com/gnea/grbl)

### Installation
STEP 1 : Download and install Arduino Iddle,  
STEP 2 : Download and unzip GRBL librarie,  
STEP 3 : Connect the arduino shield to the arduino UNO,  
![arduino_cnc](https://github.com/ghostlof/GRBL-motor/blob/master/Images/shield%20%2B%20arduino.jpg)    
STEP 4 : Add the A4988 driver on the top of X, Y and/or Z support   
![here](https://github.com/ghostlof/GRBL-motor/blob/master/Images/cnc.png),  
STEP 5 : Branch motors, switch and power supply like ![here](https://github.com/ghostlof/GRBL-motor/blob/master/Images/connect_cnc.jpg)
STEP 5 : A4988 stepper drivers need adjustment for reference voltage for that please read [this file](https://github.com/ghostlof/GRBL-motor/blob/master/Adjustment%20for%20Stepper%20Driver.md) correctly,  
STEP 6 : 

