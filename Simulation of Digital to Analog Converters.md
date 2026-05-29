## EC1421-19EC421-Analysis-and-Design-of-Analog-ICs
## SIMULATION OF DIGITAL TO ANALOG CONVERTER

## AIM:
To Design and simulate the digital to analog converter (DAC) circuit using LT Spice

## SOFTWARE REQUIRED:
LT-Spice

## PROCEDURE:
1. Double click on LT Spice icon.

2. New schematic window open.

3. Pick and paste the required component from the library and draw the circuit diagram .

4. Complete the connection.

5. Select 1 voltage and select pulse width as 
Vinitial [V]: 5
       Von [V]: 0
       Tdelay [s]: 0
       Trise [s]: 1u
       Tfall [s]: 1u
               Ton [s]: 10m
        Tperiod [s]: 20m
        Ncycles: 100
Change the values of Ton = 20m , 40m, Tperiod  = 40m , 80m
For v2 and v3  keeping the other values constant.
6. Save the file by giving file name.

7. Click on the run option -->click advanced open -->select select transient analysis -->enter the amplitude time delay stop time value as (.tran 0 200 0 0.01).

8. Click on the run option -->simulation window opens-->place the probe -->output graph is obtained.

## CIRCUIT DIAGRAM:
### DAC:
<img width="1600" height="886" alt="image" src="https://github.com/user-attachments/assets/6f416909-d332-4a98-aedb-f7ee1b0b76c4" />
<img width="989" height="1009" alt="image" src="https://github.com/user-attachments/assets/9b9fa63d-b004-4668-a815-d06aa4c69ff0" />


## OUTPUT GRAPH:
### DAC:
<img width="1600" height="835" alt="image" src="https://github.com/user-attachments/assets/8dd78b50-54b3-46c3-a80c-e1d23e64a10c" />


## RESULT:
Thus the LT-SPICE tool has been studied and digital to analog converter (DAC) circuit is simulated.
