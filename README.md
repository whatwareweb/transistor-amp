# transistor-amp
Simple transistor amplifier for Hack Club Solder 


This amplifier is based on the highly popular LM386 op-amp chip, although it has been somewhat downgraded for the sake of low component count (eg no constant current source, etc)

### Features
 - Class AB for higher efficiency
 - Runs on ~6V (2xCR2032 or external power supply input)
 - Small size, crammed in just over 3 square inches
 - Decent performance in SPICE simulation
   - higher THD than the original IC but not too bad
 - 250mW power output (yeah that's pretty low 😭)

### BOM
| Part                | Qty   | Notes                       |
| -------------       | ----- | ---                         |
| Battery holder 2032 | 2     |                             |
| 820uF Capacitor     | 1     |                             |
| Generic diode       | 2     | Needs to have 0.7v Vf       |
| 5mm terminal block  | 1     | Optional                    |
| NPN transistor      | 5     | I used 2N3904               |
| PNP transistor      | 4     | I used 2N3906               |
| 10k potentiomter    | 1     |                             |
| 10k resistor        | 2     |                             |
| 1.5k resistor       | 1     |                             |
| 15k resistor        | 1     |                             |
| 47k resistor        | 1     |                             |
| 220 ohm resistor    | 3     |                             |


### 3d view
![image](https://github.com/user-attachments/assets/95aa20b8-7a5c-4b3d-9378-3d589291443f)


### Schematic
![image](https://github.com/user-attachments/assets/14dbc77c-d9ee-4728-a314-54a4c9bcaaf8)


### PCB
![image](https://github.com/user-attachments/assets/b54b6e05-5857-4594-804f-3a218315f89a)


### Simulation results
![image](https://github.com/user-attachments/assets/1c8907fe-2911-48de-a649-2635707a95bd)


slack username: `@whatware`
