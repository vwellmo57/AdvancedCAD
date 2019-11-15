# Intermediate CAD
## Assignments such as Gears, Gear Box, Motion Study, and Stress Analysis 

### Gear/Gearbox:
#### Objective
Create a gear with multiplue configurations and then using that make a gear box. 
#### The Process
I started

#### Important Code
`LEDFade.py`
``` python
    
while True: #essesialy a void loop
    for I in range(0, 65535, 1): #counts from 0 to 65535 and then writes it to the LED
        analog_out.value = i
    for j in range(65535, 0, -1): #counts from 65535 down to 0 and then writes it to the LED
        analog_out.value = j
```
Our variable counts up, but once it reaches 6000, it multiplies it by a negative and it counts down until it reaches 2000, where it begins to count up. 
