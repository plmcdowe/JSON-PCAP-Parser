# Purdue CS, MS.
## [ \* json PCAP parsing ](https://github.com/plmcdowe/School/tree/1228ab2c2261ae7d5b3b14264a321303cdc0361b/Purdue-CS/JsonPCAP-Parser)
> Split between two files due to the nature of the orignial assignment.   
> The structure of either/both program could be extended to examine PCAPs for additional security events.
> 
> [ JsonPCAP1.py ](https://github.com/plmcdowe/School/blob/68bad203da6eec271042d636ce8111531ddbe056/Purdue-CS/JsonPCAP-Parser/JsonPCAP1.py) parses for:   
>> \> *Successful* HTTP sessions   
>> \> Directory Traversal evidence   
>> \> Failed login attempts   
>> \> Clear text credentials   
>> \> Apache webserver versions   
>> \> DNS source port randomization   
>> \> TCP ISN deviation   
>> \> Traceroute evidence   
>> \> XSS evidence
>> 
> [ JsonPCAP2.py ](https://github.com/plmcdowe/School/blob/66482f5573c2977825d1fe7e7c897acf34860bb2/Purdue-CS/JsonPCAP-Parser/JsonPCAP2.py) parses for:   
>> \> Client MAC & IP addresses   
>> \> FTP session details   
>> \> Facebook URIs & cookies   
>
---
# Personal projects
## [ \* Picture Robot ](https://github.com/plmcdowe/School/tree/1228ab2c2261ae7d5b3b14264a321303cdc0361b/PersonalProjects/PictureRobot)  
> An Arduino robot controlled through Python to copy physical photographs with a DSLR camera.   
>> The Arduino Uno + Adafruit Motor Shield drives:   
>> \> Six, 5v 28BYJ-48 stepper motors   
>> \> One, 12v vacuum pump   
>> \> One, HC-SR04 sonar sensor   
>> \> One, MMA8452 accelerometer   
>> \> Triggers a Nikon DLSR through a hacked-up MC-DC2 Remote Release Cord   
>>    
> [ Robot_GUI.py ](https://github.com/plmcdowe/School/blob/1228ab2c2261ae7d5b3b14264a321303cdc0361b/PersonalProjects/PictureRobot/Robot_GUI.py) provides control over serial through a Tkinter GUI.   
> [ TkinterRobot.ino ](https://github.com/plmcdowe/School/blob/1228ab2c2261ae7d5b3b14264a321303cdc0361b/PersonalProjects/PictureRobot/TkinterRobot.ino) is the Arduino program to drive the hardware.   

Demo of the python GUI interacting over serial with the Arduino to turn on a blue LED:   

https://github.com/user-attachments/assets/d8e87a40-d99c-4695-b16d-e683b1de0d4c
