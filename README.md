#  8×8×8 LED Cube

> A 3D matrix of 512 LEDs controlled by a microcontroller — Hardware meets Software!

---

##  About The Project

The 8×8×8 LED Cube is a hardware project consisting of 512 LEDs arranged in a three-dimensional matrix. The cube displays stunning 3D lighting patterns and animations using multiplexing techniques, all controlled by a microcontroller programmed in Embedded C. This project demonstrates the intersection of electronics engineering and software programming.

---

##  Key Features

-  **512 LEDs** arranged in 8×8×8 3D matrix
-  **Multiplexing Technique** — Controls all LEDs efficiently with minimal pins
-  **Multiple Animation Patterns** — Wave, spiral, rain, bounce effects
-  **Microcontroller Programmed** in Embedded C
-  **Custom PCB Design** for clean circuit layout
-  **Low Power Consumption** with efficient multiplexing

---

##  Tech Stack

| Component | Details |
|---|---|
| Microcontroller | Arduino / ATmega328P |
| Programming Language | Embedded C |
| LEDs | 512 × 5mm LEDs |
| Technique | Multiplexing (layer-by-layer scanning) |
| Tools | Arduino IDE, Proteus (simulation) |

---

##  Circuit Design

```
Layer Control (8 pins) → Transistors → LED Layers (8)
Column Control (64 pins) → Shift Registers → LED Columns
Microcontroller → Controls timing & pattern logic
```

---

## Project Structure

```
8-8-8-LEDCUBE/
├── code/
│   ├── main.ino              # Main microcontroller code
│   ├── patterns.h            # LED animation patterns
│   └── multiplexing.h        # Multiplexing logic
├── circuit/
│   ├── schematic.pdf         # Circuit diagram
│   └── pcb_layout.pdf        # PCB layout
├── images/
│   └── cube_photo.jpg        # Project photos
└── README.md
```

---

##  How To Upload Code

```bash
# Open Arduino IDE
# Select board: Arduino Uno / ATmega328P
# Select correct COM port
# Open main.ino
# Click Upload
```

---

##  Animation Patterns

| Pattern | Description |
|---|---|
| Rain | LEDs fall from top to bottom |
| Wave | Sine wave sweeps across cube |
| Spiral | LED spiral from center outward |
| Bounce | Ball bouncing inside the cube |
| Plane Sweep | Horizontal planes light up sequentially |

---

##  Build Steps

1. Solder 512 LEDs in 8×8×8 grid (8 layers × 64 LEDs)
2. Connect layer anodes to transistors
3. Connect column cathodes to shift registers
4. Connect shift registers to microcontroller
5. Upload code and power on!

---

##  Developer

**Lekhashree B** — [LinkedIn](https://linkedin.com/in/lekhashree-b) | [GitHub](https://github.com/lekhashree21)
