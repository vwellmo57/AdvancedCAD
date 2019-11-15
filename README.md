# Intermediate CAD
## Assignments such as Gears, Gear Box, Motion Study, and Stress Analysis 

### Gear/Gearbox:
#### Objective
Create a gear with multiple configurations and then using that make a gear box. 
#### The Gears
I started by creating all of the nessesary equations, by the way, PI, is pie. Then I created the basic geometry using construction circles, it is crucial that you type in "=pitchDiameter" + 2 * "addendum" and not "pitchDiameter" + 2 * "addendum" because the latter will auto solve and become a fixed dimension. You know you've done it right when the sigma for equations is present. the rest of the construction is fairly straightforward. Then I created the 4 configurations, this is all pretty simple by following instructions and referencing the configurations assigments. the I just cut holes and made the gears gold. 

#### The Box

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
