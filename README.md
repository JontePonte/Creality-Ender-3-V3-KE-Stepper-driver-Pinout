Here's how to use the stepper motor drivers on the Creality Ender-3 V3 KE board:

| TP-pin | Funktion                  |
|--------|---------------------------|
| TP16   | Enable (all motors)       |
| TP14   | X Step                    |
| TP13   | X Dir                     |
| TP17   | Y Step                    |
| TP15   | Y Dir                     |
| TP20   | Z Step                    |
| TP18   | Z Dir                     |
| TP21   | E Step                    |
| TP19   | E Dir                     |


These pins expose the internal stepper drivers of the Ender-3 V3 KE board. 
After soldering connectors, you can directly control X, Y, Z, and E motors with any 3.3V logic MCU such as ESP32 or Arduino.
