# MFight

**A 1V1 battle game with many kinds of weapons and effects**  
**Please ignore the grammar and spelling mistakes in this README.md**

## Controlling

### Player A (Red)
Use `Uparrow`,`Leftarrow`,`Downarrow` and `Rightarrow` to move.  
Use `,` to fire and `.` to change weapon.  

### Player B (Blue)
Use `W`,`A`,`S` and `D` to move.  
Use `G` to fire and `H` to change weapon.

## How to play with AI
A built-in AI is in the code.  
Just uncomment the `update` function at the end of the code.
The AI is very strong.

## Effects, Packets and Weapons

### Effects
Effects will be shown at the top of the screen.  
Good effects are colored with Blue;  
Bad effects are colored with Red.

#### Acid
The packet of it is colored with limegreen.  
If you pick it, you will have a good effect named Acid for 300 ticks(a tick is 1/60 second). In this peroid of time, every shot comes from you will have Acid effect;  
If you got a shot with Acid, you will have a bad effect called Acid for 100 ticks. In this peroid of time, you will lose you health at the speed of 1/20 for one tick.Acid is the only bad effect that can be have for more than one.

#### Lockdown
The packet of it is colored with purple.  
If you pick it, you will have a good effect named Lockdown for 400 ticks. In this peroid of time, every shot comes from you will have Lockdown effect;  
If you got a shot with Lockdown, you will have a bad effect called Lockdown for 200 ticks. In this peroid of time, you will not be able to move;    
You will also get a good effect called Lockdown_resistance for 400 ticks.In this peroid of time, you won't get Lockdown(bad) for a second time.

#### Suppression
The packet of it is colored with red.  
If you pick it, you will have a good effect named Suppression for 600 ticks. In this peroid of time, every shot comes from you will have Suppression effect;  
If you got a shot with Suppression, you will have a bad effect called Suppression for 400 ticks. In this peroid of time, the damage cause by your bullet will be half;     
You will also get a good effect called Suppression_resistance for 700 ticks.In this peroid of time, you won't get Suppression(bad) for a second time.

#### ICE
The packet of it is colored with lightblue.  
If you pick it, you will have a good effect named Ice for 400 ticks. In this peroid of time, every shot comes from you will have Ice effect;  
If you got a shot with Ice, you will have a bad effect called Ice for 300 ticks. In this peroid of time, the damage cause by your enemy's bullet will be increased by half;     
You will also get a good effect called Ice_resistance for 700 ticks.In this peroid of time, you won't get Ice(bad) for a second time.

#### Heal
The packet of it is colored with freshgreen.
If you pick it, you will have a good effect named Heal for 300 ticks. In this peroid of time, your health will increase at the speed of 1/2 per tick;  
There is a limit of your health which is the damage you recieved divided by 2.

### Weapons
Weapons will be shown at the top of the player with color orange.  
The weapons in this game are Gun(G), Sniper(S), Machine gun(M) and Shotgun(H).

### Shield
The packet of it is colored with cornflowerblue.  
If you pick it:
- if you already have a shield, your shield will be charged suddenly to 30 health.  
- else, you will have a shield with 30 health.  

If your shield is not at the health of 30, the health of it will increase slowly at the speed of 1 per second.  
If your shield has been damaged to 0 health, you will lose it.
