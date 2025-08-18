# August 17
Today, i learnt about how an ESC works, so basically there is an MCU, and mosfets and their gate drivers, and the MCU switches really fast the MOSFETS which makes then imitate the generation of 3-phase AC, which drives the motor. There is a high side mosfet and a low side mosfet, though i dont still get what these 2 sides means and how is AC made with DC lol.

I think i have decided a few ICs as they are very popular, they are BB21 something MCU, FD6288 three phase driver. BSC007N04LS6 MOSFET was selected by me as i liked it so much on LCSC. 

![mosfet](/images/17.8/mosfet.png)

### Time Spent Today: 1 hour

# August 2 2025
Well idk when did i start with the schematic, but i did a bit of work. I will be doing for a single motor at a time and then just copy paste for 4. because that is what has to be done i guess.

well i did the mosfet connections for it, and now connected them to the driver too  
there are 2 mosfets per motor per phase and 3 phases so total 6 mosfets per motor.  
i still have to figure out the use of VB1,2,3 pins on the MOSFET driver  

did some work on the schematic, 
![1st pic](/images/18.8/mcu%20and%20mosfet%20driver.png)
![2nd pic](/images/18.8/mosfets.png)

### Time spent today: 45 mins