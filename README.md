# -LED-Flip-Flop-Circuit

# LED Flip-Flop Circuit PCB

## 📌 Project Overview

This project is a **LED Flip-Flop Circuit PCB** designed using **KiCad**.

The circuit alternately switches between two LEDs, creating a simple blinking/flip-flop effect. The PCB was designed to provide a compact and organized implementation of the circuit using standard electronic components.

The project focuses on the complete PCB design process, including schematic creation, footprint assignment, component placement, PCB routing, and Design Rules Check (DRC).

---

## 🎯 Project Objectives

- Design a simple LED flip-flop circuit.
- Create the schematic in KiCad.
- Assign suitable footprints to all components.
- Design a compact PCB layout.
- Route all electrical connections properly.
- Add PCB labels and component references.
- Perform ERC/DRC checks before fabrication.
- Generate manufacturing files when required.

---

## ⚙️ Working Principle

The LED flip-flop circuit uses a transistor-based switching arrangement to alternately turn two LEDs ON and OFF.

When one transistor conducts, one LED is activated while the other remains OFF. The circuit then changes state, causing the LEDs to switch alternately.

### Basic operation

``
        +VCC
         │
      ┌──┴──┐
      │     │
     LED1  LED2
      │     │
     Q1     Q2
      │     │
      └──┬──┘
         │
        GND

   Q1 and Q2 alternately switch ON/OFF

🧩 PCB Design Process
1. Schematic Design

The circuit schematic was created in KiCad with all components and electrical connections.

2. Footprint Assignment

Suitable PCB footprints were assigned to each component based on the physical component/package being used.

3. PCB Layout

The schematic was transferred to the PCB Editor and the components were arranged to create a compact and organized board.

4. Routing

Copper tracks were routed between the components according to the schematic connections.

5. Design Rules Check

The PCB was checked using KiCad's Design Rules Check (DRC) to identify issues such as:

Clearance violations
Unconnected nets
Track width violations
Pad clearance problems
Board-edge clearance problems
6. Final Verification

The PCB layout was visually inspected and checked before preparing the manufacturing files.

📐 PCB Features
Compact PCB layout
Two alternating LEDs
Through-hole/component footprints where applicable
Clearly marked component references
Dedicated power input
Organized component placement
KiCad DRC verification
Suitable for PCB fabrication

🚀 Future Improvements

Possible improvements include:

Add a power indicator LED
Add adjustable blinking speed
Use a potentiometer for frequency control
Improve PCB size and component placement
Add mounting holes
Add polarity and power markings
Manufacture and test the PCB
Create an SMD version of the circuit
📚 Learning Outcomes

Through this project, the following PCB design skills were practiced:

KiCad schematic design
Component and footprint selection
PCB component placement
Through-hole PCB design
Copper track routing
PCB layout optimization
ERC and DRC checking
Gerber generation
PCB documentation
🛠️ Tools & Technologies

Design Software: KiCad
PCB Design: KiCad PCB Editor
Schematic: KiCad Schematic Editor
Verification: ERC / DRC
Output: Gerber + Drill Files

 Project

LED Flip-Flop Circuit PCB

Designed as a practical electronics PCB design project using KiCad.
