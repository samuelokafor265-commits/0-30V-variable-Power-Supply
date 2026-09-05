# 0–30 V Variable DC Power Supply

 Project Overview

A variable DC power supply designed and built as a practical electronics project. The supply provides an adjustable DC output from 0 V to 30 V and was developed through three stages:

Circuit simulation → Breadboard prototype → Veroboard implementation

The project was simulated in Proteus before being physically prototyped and subsequently assembled on Veroboard and enclosed in a plastic casing.

The project was intended to provide a simple, adjustable DC source for powering and testing electronic circuits, sensors, microcontrollers, and other low-voltage electronics.

## Key Specifications

| Parameter          | Specification                       |
| ------------------ | ----------------------------------- |
| Output voltage     | 0–30 V DC                           |
| Output type        | Variable DC                         |
| Construction       | Veroboard                           |
| Initial prototype  | Breadboard                          |
| Circuit simulation | Proteus                             |
| Enclosure          | Plastic casing                      |
| Voltage adjustment | Potentiometer                       |
| Application        | Electronics testing and prototyping |

> Note: The maximum output current depends on the power supply components and regulator configuration used in the build.

 Development Process

1. Circuit Design

The circuit was first designed based on the required output voltage range of **0–30 V DC**.

Component values were calculated according to the requirements of the voltage regulation stage, and the circuit was designed to allow the output voltage to be adjusted using a potentiometer.

### 2. Proteus Simulation

Before building the physical circuit, the design was simulated using **Proteus Design Suite**.

The simulation was used to:

* Verify the circuit topology
* Check the expected output voltage
* Test the voltage adjustment range
* Identify potential circuit errors
* Validate component values before physical construction

### 3. Breadboard Prototype

After successful simulation, the circuit was assembled on a breadboard.

The prototype was tested by applying the input supply and gradually adjusting the potentiometer while measuring the output voltage using a multimeter.

This stage helped verify that the physical circuit behaved consistently with the simulated design.

### 4. Veroboard Construction

After validating the breadboard prototype, the circuit was transferred to Veroboard to create a more permanent implementation.

The components were soldered onto the board, with the circuit tracks modified where necessary to create the required connections.

### 5. Enclosure

The completed Veroboard circuit was installed inside a plastic enclosure.

The enclosure was used to:

* Protect the circuit
* Improve portability
* Reduce accidental contact with the circuitry
* Provide a more finished and practical assembly

## System Architecture

```text
             INPUT DC
                │
                ▼
        ┌─────────────────┐
        │ Voltage          │
        │ Regulation Stage │
        └────────┬────────┘
                 │
                 ▼
        ┌─────────────────┐
        │ Voltage          │
        │ Adjustment       │
        └────────┬────────┘
                 │
                 ▼
             0–30 V DC
              OUTPUT
```

 Testing

The output voltage was measured using a digital multimeter while adjusting the control potentiometer.



This project provided practical experience in:

* Electronic circuit design
* Voltage regulation
* Component selection
* Circuit simulation using Proteus
* Breadboard prototyping
* Veroboard construction
* Soldering and circuit assembly
* Circuit troubleshooting
* Multimeter-based testing
* Enclosure design and physical integration

One of the main objectives of the project was to validate the design progressively, moving from simulation to a physical prototype before producing the final enclosed implementation.

## Future Improvements

Possible future improvements include:

* Adjustable current limiting
* Over-current protection
* Short-circuit protection
* Over-temperature protection
* Reverse-polarity protection
* Improved output filtering
* Higher efficiency
* PCB implementation instead of Veroboard

## Tools & Equipment

**Software**

* Proteus 8 Design Suite

**Hardware**

* Breadboard
* Veroboard
* Digital multimeter
* Soldering equipment
* DC power source
* Electronic components
* Plastic enclosure

Components Used
LM723 Voltage Regulator IC
Q1: 2N3055 NPN Power Transistor
Q2: BD140 PNP Transistor
Q3: 2N3906 PNP Transistor
BR1: Bridge Rectifier
R1: 10kΩ Resistor
R2: 10kΩ Resistor
R3: 10kΩ Resistor
R4: 10kΩ Resistor
R5: 10kΩ Resistor
R6: 200Ω Resistor
R7: 300kΩ Resistor
R8: 100kΩ Resistor
R9: 5kΩ Resistor
R10: 10kΩ Resistor
R11: 10kΩ Resistor
R12: 100kΩ Resistor
R13: 100kΩ Resistor
RES: 10kΩ Resistor
C5: 4700µF Capacitor
C3: 1nF Capacitor
C2: 680pF Capacitor
C_ (near output): 100µF Capacitor
C1: 0.1µF Capacitor
SW1: SW-SPST (Single-Pole Single-Throw Switch)
J3: TBLOCK-I4 (4-pin Terminal Block)
J2: CONN-SIL3 (3-pin Single-In-Line Connector)
J1: TERMINAL (Output Test Point)
Power cord
Center Tapped Transformer

