# hardware-task-3

MOSFET LED Switching Project

This project demonstrates the basic functionality of an N-Channel MOSFET used as a switch to control an LED using a 220Ω resistor. The control is done manually using jumper wires — no microcontroller is involved.

Components Used

1.N-Channel MOSFET (IRF540N)

2.LED (green)

3.220Ω resistor (used for both LED current limiting and Gate pull-down)

4.Breadboard

5.Jumper wires

5.Power source (9V battery)

Circuit Diagram Explanation

1.VCC → 220Ω resistor → LED anode

2.LED cathode → MOSFET Drain

3.MOSFET Source → Ground

4.MOSFET Gate → VCC via jumper wire (to turn ON)

5.MOSFET Gate → Ground via 220Ω resistor (pull-down to keep OFF)

Step-by-Step Instructions

1.Place the LED on the breadboard with legs in separate rows.

2.Connect a 220Ω resistor to the LED anode and then to VCC.

3.Connect the LED cathode to the MOSFET Drain.

4.Connect the MOSFET Source to Ground.

5.Connect the Gate to VCC using a jumper wire or source to ground to turn the LED ON.

6.Add a 220Ω resistor between Gate and Ground to keep the MOSFET OFF when not driven.


Observations
1.When Gate is connected to VCC or source is connected to ground, the MOSFET turns ON and the LED lights up.

2.When Gate is disconnected or grounded or source is not connected to ground, the MOSFET turns OFF and the LED stays off.

3.The MOSFET acts as a low-side switch, controlling the path to ground.

