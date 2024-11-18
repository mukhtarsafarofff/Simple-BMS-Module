(ENG) To control the process of charging and discharging of Lithium ion or LiPo batteries, they will stop working or worse. The battery cells can swell and even explode from overcharging, and a deep discharge can make the battery fail. That’s why these batteries should go together with a battery management system unit or BMS. This will control the voltage and current from the battery and keep them safe.

(DEU) Um den Lade- und Entladevorgang von Lithium-Ionen- oder LiPo-Batterien zu steuern, müssen sie richtig überwacht werden, sonst funktionieren sie nicht oder es kann noch schlimmer kommen.  Die Batteriezellen können bei Überladung anschwellen und sogar explodieren, und eine Tiefentladung kann die Batterie unbrauchbar machen. Deshalb sollten diese Batterien immer zusammen mit einer Batterie-Management-System-Einheit (BMS) verwendet werden.  Diese steuert die Spannung und den Strom der Batterie und hält sie sicher. Die Nennspannung einer LiPo-Batterie beträgt 3,8 Volt und 4,2 Volt, wenn sie vollständig geladen ist. Sobald die Batteriezelle diesen Wert erreicht, sollte der Ladevorgang gestoppt werden, und genau das soll diese Schaltung tun. Wenn wir nur eine Zelle haben, kümmern wir uns nur um die maximale Spannung und den Stromgrenzwert, um die Batterie zu schützen. Aber wenn wir ein Batteriepack mit mehr als einer Zelle haben, also 2S, 3S und so weiter, müssen wir auch den Wert jeder einzelnen Zelle ausbalancieren. An der Basis des Transistors haben wir eine Z-Dioden-Referenz (TL431), die bei einem bestimmten Spannungswert öffnet und damit die Basis des Transistors mit Masse verbindet. Wenn der Transistor aktiv ist, umgehen wir die Batterie und verbrauchen die Energie stattdessen an den Dioden. Diese Z-Diode ist die TL431 und sie hat einen Referenzpin. Durch Einstellen des Potentiometers können wir diese Referenz auf 4,2 Volt einstellen, wodurch wir festlegen, wann der Ladevorgang gestoppt wird. Um die Schaltung zu testen, benutze ich eine Batterie, die entladen ist und unter 4,2 Volt liegt (sie hatte 3,8 Volt). Wenn ich sie an das Ladegerät anschließe, ist die LED ausgeschaltet. Ich habe einen Stromfluss von etwa 450 mA und die Batterie wird aufgeladen.  Nach einiger Zeit, wenn wir über 4,16 Volt erreichen, wird die LED eingeschaltet, sodass der Ladevorgang abgeschlossen ist. Der Strom fließt jetzt durch die Dioden und den Transistor und wir umgehen die Batterie, sodass die Zelle vor Überspannung geschützt ist.
