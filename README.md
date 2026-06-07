# Guitar-Amp
## Description
A 4 inch and electric guitar amplifier using the LM386n-4 and J201 JFETS. Operates using 4 main stages:
1. JFET input boost, the signal coming from a guitar is very weak, so it needs to be boosted to a usable level
2. Tone control, uses a 50k POT to control the guitars tone, this stage decreases the signal strength
3. JFET tone boost, boosts the signal strength back up to usable level.
4. Audio amplification, uses the LM386n-4 to amplify the audio to ~1w, ideal for a 4 inch speaker

![image](https://cdn.hackclub.com/019e9fdd-3187-77df-ac26-52c6853343bf/image.png)

The board is designed to use only THT components to save money as it can ban easily soldered with basic tools, to aid in the easy assembly parts are also spread out over a almost 200mm width. Components start on the left with the 1/4 inch jack input, wrap around the top, and end on the right with the speaker output. It is mounted to the case using m2 screws.

![image](https://cdn.hackclub.com/019e9fdd-a5a9-7dbc-9905-32098cbfd932/image.png)
![image](https://cdn.hackclub.com/019e9fdd-f783-7cd4-8558-62f001f99fa9/image.png)

The case is pretty simple, just a speaker on the front with the three potentiometers and input jack up top, the 12v barrel is located on the back of the case near the bottom, the case is printed in two parts, the back plate is printed seperatly and screwed on with two M2 screws.

![image](https://cdn.hackclub.com/019e9fe9-2b23-7af3-9cb2-68ee4dcb35a5/image.png)  

Inside mounting holes of back plate:  

![image](https://cdn.hackclub.com/019e9fe9-975e-72a4-864f-15d8751d81e0/image.png)

## Instructions
### Build 
1. Solder components onto the pcb, simply solder the through hole components, no special gear is needed.
2. Wire potentiometers, the input jack, 12v barrel, and the speaker. Solder using 22AWG wire to thier respective pads
3. Print case in any orientation prefered, note that supports will be needed for the main body.
4. Screw in components, the pcb and backplate use m2 screws, and the speaker uses m8.


### Usage
1. Plug in guitar, reccomend starting with this to avoid a loud, high piched noise.
2. Plug in 12v barrel to turn on amp
3. Adjust knobs to prefered tune
4. Play your guitar!

## Why I made this
Pretty simple, I don't have an AMP, but I do have a guitar (I actually built it myself). After building I decieded that I wanted to learn to play, until this I had been plugging it into my old ipod and using garage band as an amp, but this was pretty terrible so I decieded this would be a fun first hardware project
