To control the process of charging and discharging of Lithium ion or LiPo batteries, they will stop working or worse. The battery cells can swell and even explode from overcharging, and a deep discharge can make the battery fail. That’s why these batteries should go together with a battery management system unit or BMS. This will control the voltage and current from the battery and keep them safe. The nominal voltage of a LIPO battery is 3.8 volts and 4.2V when fully charged. As soon as the battery cell will reach this value, the charging process should stop and that’s what this circuit should do. When we have only one cell, we only care about the maximum voltage and the current limit to protect the battery. But when we have a battery pack of more than 1 cell, so 2S, 3S and so on, we also need to balance the value of each individual cell.  At the base of the transistor, we have a ZENNER reference diode (TL431) which will get open at a certain voltage value and by that connects ground to the transistors base and when the transistor is active, we bypass the battery and waste the power on the diodes instead. This ZENNER diode is the TL431 and it has a reference pin, so by adjusting the potentiometer we can set this reference to be at 4.2V, that’s how we select when the charging process will stop. To test the circuit , I  use a battery which is discharged and below 4.2V (it was 3.8V). When I connect it to the charger, the LED is turned off. I have a current flow of around 450 mA and the battery is getting charged up. After some time, when we get above 4.16V the LED will turn ON so the charging process is complete. Current is now flowing through the diodes and transistor and we skip the battery, so the cell is protected for over voltage.

Um den Lade- und Entladevorgang von Lithium-Ionen- oder LiPo-Batterien zu steuern, müssen sie richtig überwacht werden, sonst funktionieren sie nicht oder es kann noch schlimmer kommen. 
