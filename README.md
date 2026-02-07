# Blinkenstein

Blinkenstein is a KiCad PCB design based on a few simple electronic components, 
intended to be a simple PCB test project, for example, 
for testing home boards or for companies offering professional PCB services.

## How it works?

Blinkenstein can be powered by a DC power supply with an output voltage between 7-12V; 
it's worth adding a safety margin, so I recommend a 9V power supply. 
The circuit doesn't draw much current; about 100mA is sufficient. 
The circuit operates by alternating the color of the LEDs from `RED -> GREEN -> BLUE -> YELLOW`. 
It's not a disco light, but rather a toy, because despite having eight LEDs, 
only two can illuminate at a time. The heart of the circuit is the CD4017, 
whose input receives 'inverted pulses' from a generator based on the **tunneling effect**. 
The signal passes to a NOT gate with a _Schmitt input_, which 'rectifies' the waveform.

You will find the necessary files in this folder:
> _**[Click here](/konstantynopolitanczykowianeczka_zamieszkujaca_konstantynopol)**_
