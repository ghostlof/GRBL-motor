# Les différentes bibliothèques possibles
* https://all3dp.com/2/best-cnc-software-for-arduino/		

# Slider
* https://www.amazon.com/FUYU-Linear-Actuator-Motorized-Stepper/dp/B077Q8T6Y3
* https://www.technic-achat.com/moteur-pas-a-pas-23,fr,4,MPP_23_XX.cfm?gclid=EAIaIQobChMI3a7UrOrd6gIVVofVCh0c7w4vEAAYAiAAEgJKK_D_BwE
* https://www.amazon.fr/Couette-23-Moteur-1-26-Nm-conducteur-Imprimante/dp/B06XVC23Z7/ref=sr_1_5?dchild=1&keywords=Nema+23+Stepper+Motor&qid=1595316851&sr=8-5


# Driver moteur + CNC Shield
* https://www.banggood.com/fr/Geekcreit-UNO-R3-With-4pcs-A4988-Driver-With-CNC-Shield-V3-Expansion-Board-For-Arduino-3D-Printer-p-967060.html?gmcCountry=FR&currency=EUR&createTmp=1&utm_source=googleshopping&utm_medium=cpc_bgs&utm_content=frank&utm_campaign=frank-ssc-fr-css-all-19cov-0403&ad_id=429902602762&gclid=EAIaIQobChMIut2a8fXd6gIVA4fVCh1hrQIREAQYAyABEgLWk_D_BwE&cur_warehouse=CN
* https://www.cours-gratuit.com/cours-arduino/tutoriel-arduino-et-grbl-avec-cnc-shield-v3-pdf
* https://www.gotronic.fr/art-driver-de-moteur-pas-a-pas-a4988-1182-21718.htm
	
# Listes paramètres en Gcode
* https://wiki.shapeoko.com/index.php/G-Code#Machine_Options_.28M.29
* http://www.barrel-organ-discovery.org/site/wiki/articles/Percage_GCode/PARAM%C3%88TRES%20DU%20GRBL_JPR_Freddy.pdf
* http://www.linuxcnc.org/docs/2.4/html/gcode_overview.html#sec:Modal-Groups
* http://gcodeimpression3d.eu/co/commandesPrincipales.html


# Bibliothèque GRBL
* https://github.com/grbl/grbl/wiki/Configuring-Grbl-v0.8
* https://github.com/grbl/grbl/wiki/Configuring-Grbl-v0.9
* https://github.com/gnea/grbl/wiki/Grbl-v1.1-Configuration
* https://github.com/gnea/grbl
* https://github.com/gnea/grbl/wiki


# Listes commandes GRBL
* https://github.com/gnea/grbl/wiki/Grbl-v1.1-Commands
* https://github.com/gnea/grbl/blob/master/doc/markdown/commands.md
* https://github.com/gnea/grbl/wiki/Grbl-v1.1-Configuration#grbl-settings
* https://lebearcnc.com/configurer-et-parametrer-grbl/
* http://www.diymachining.com/downloads/GRBL_Settings_Pocket_Guide_Rev_B.pdf


# Listes erreurs
* http://domoticx.com/cnc-machine-grbl-error-list/
* https://github.com/gnea/grbl/wiki/Grbl-v1.1-Interface#grbl-response-messages


# Homing Cycle
* https://github.com/gnea/grbl/wiki/Set-up-the-Homing-Cycle
* https://github.com/gnea/grbl/wiki/Grbl-v1.1-Configuration#27---homing-pull-off-mm

# Branchement switchs
* http://mon-club-elec.fr/openmakermachine/
* http://mon-club-elec.fr/openmakermachine/pdf/dossier_construction_open_maker_machine_v1.pdf
* http://mon-fablab.fr/simplecncmillboard/pour_comprendre
* https://github.com/gnea/grbl/wiki/Wiring-Limit-Switches

# Infos sur les paramètres 
$100, $101, $102 : le nombre de pas par mm pour chaque axe. Ceci dépend du type de châssis que vous avez choisi pour la CNC : https://blog.prusaprinters.org/calculator_3416/
$110, $111, $112 et $120, $121, $122 : définissent respectivement la vitesse en mm/min et l’accélération en mm/sec²
* http://lesporteslogiques.net/wiki/outil/cnc_colinbus-configuration

# Paramètres moteurs + CNC
* http://www.zyltech.com/arduino-cnc-shield-instructions/
On est en full stepp car M0=M1=M2=LOW
* https://howtomechatronics.com/tutorials/arduino/how-to-control-stepper-motor-with-a4988-driver-and-arduino/
* https://www.lesimprimantes3d.fr/forum/topic/10459-pi%C3%A8ges-des-r%C3%A9glages-vref-a4988-ou-drv8825/


		Python
http://fablab37110.ovh/doku.php?id=start:cnc:grbl
