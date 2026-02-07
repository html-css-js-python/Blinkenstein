# Blinkenstein

Blinkenstein is a KiCad PCB design based on a handful of simple electronic components.
It is intended as a small PCB test project — useful for testing homemade boards
or for companies offering professional PCB manufacturing services.

## How it works

Blinkenstein can be powered by a DC power supply with an output voltage of 7–12 V.
A 9 V supply is recommended as a safe and convenient choice.
The circuit draws very little current; around 100 mA is sufficient.

The circuit operates by cycling the LED colors in the following order:
`RED → GREEN → BLUE → YELLOW`.
Despite having eight LEDs, only two can be illuminated at the same time,
so this is more of a toy than a disco light.

At the heart of the circuit is a CD4017 decade counter.
Its clock input receives inverted pulses from a generator based on the
**tunneling effect**.
The signal then passes through a NOT gate with a *Schmitt trigger input*,
which cleans up the waveform.

You will find all required files in this folder:
> **[Click here](/konstantynopolitanczykowianeczka_zamieszkujaca_konstantynopol)**
