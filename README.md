# Storing-and-Moving-Text-
Design a circuit capable to store short messages and to display them as a scrolling marquee on the four 7-segment LEDs.

esign  a  circuit  that  can  store  and  display  an  arbitrary messagewhich  has  been  entered  character  by  character  by  the  user.  The  characters will be entered using the 8DIP. For simplicity, you may assume that the total length of the entered message will be no longer than 20 characters. To remain consistent you must use the following mappings for the DIP switches:

SW7 -segA, SW6 -segB, SW5 -segC, SW4 -segD, SW3 -segE, SW2 -segF, SW1 –segG, SW0 –segDP

Use the three push-buttons to determine the state of your machine. All possible states of the machine are given below:

![image](https://user-images.githubusercontent.com/88007099/127400573-37bdf10e-7a84-4bbe-b02d-dcfe57ad4431.png)

In other words, when (BTN2,BTN1,BTN0) =(110),the user modifies the switches  to  the  letter  they  want  to  be  loaded  and  stored.  Then,  when  (BTN2,BTN1)=(11)  andBTN0  goes  from  0  to  1,  the  letter  is  loaded  and  stored  into the  proper  register.  To  load  and  store  the  next  letter  the  user  only  needs  to  set BTN0  =  0  again  (let  go  of  the  pushbutton),  modify  the  switches,  and  then  to switch the BTN0 from 0 to 1. These actions take place as long as the user wants to  introduce  letters  or  the  blank  character  (the  blank  character  is  simply  an "empty" character, when nothing is displayed by the 7-segment LED). 
