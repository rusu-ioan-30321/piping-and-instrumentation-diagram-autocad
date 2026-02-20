# Evaporation Process Control System – AutoCAD P&ID

## Project Overview
This project consists of a Piping and Instrumentation Diagram (P&ID) of an automated evaporation process, created in AutoCAD using PIP standards.

The system models a vapor generation, compression, and recycle control process involving two tanks and multiple instrumentation loops.

## Process Description

The process begins in the **Evaporator (Tank 1)**, where vapor is generated and exits through the top outlet.

The vapor flow:
1. Passes through a **Flow Transmitter (FT)**
2. Enters a **Compressor**
3. Is delivered at constant pressure into the **Knockout Drum (Tank 2)**

### Recycle Line
A secondary main pipe from the compressor includes a **recycle control valve**.

The recycle valve:
- Returns excess vapor into the system
- Activates when excess flow is detected
- Prevents overfilling of the knockout drum
- Maintains compressor safety and system stability

## Instrumentation & Control

### Flow Control Loop (Loop 42)
- Flow Transmitter (FT)
- Pressure Differential Transmitter (PDT)
- Flow Indicating Controller (FIC)
- Control Valve

The FIC receives:
- Flow data from FT
- Differential pressure data from PDT

Based on these signals, it regulates the recycle valve to control vapor flow.

### Temperature Monitoring
Two secondary lines include:
- Temperature Transmitter TT-41
- Temperature Transmitter TT-43

Each sends data to panel-mounted:
- Temperature Indicators
- Temperature Controllers

## System Components
- Evaporator (Boiler)
- Compressor
- Knockout Drum
- Control Valve (Recycle)
- Flow Transmitter
- Pressure Differential Transmitter
- Temperature Transmitters
- Flow & Temperature Controllers
- Primary and secondary piping network

## AutoCAD Tools & Standards Used
- PIP Standard Symbols
- Tool Palettes
- Assign Tag
- Validate (diagram verification)
- PAN
- Standard drawing and annotation tools

## Technical Focus
- Closed-loop control system design
- Instrument tagging and loop numbering
- Industrial P&ID standards
- Signal flow representation (electrical signals)
- Process safety via recycle control logic

## What I Learned
- Designing an automated industrial control system
- Implementing feedback control loops
- Applying PIP standards in P&ID drawings
- Structuring instrumentation logic in process systems
