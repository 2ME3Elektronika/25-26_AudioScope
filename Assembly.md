# STEPS TO ASSEMBLE THE AUDIOSCOPE

## PRE-ASSEMBLY & PREPARATION
Before starting the physical construction, ensure you have completed these essential preparatory steps to ensure the "Brain" of the project is ready.

### 1. Software & Firmware Setup
Since the project is based on a Raspberry Pi, it is highly recommended to flash the OS and install the necessary drivers before mounting it inside the cage:
* **Flash the OS:** Install the required OS (Raspbian/Lite) onto your SD card.
* **Enable Interfaces:** Enable **I2C** and **I2S** interfaces via `raspi-config`.
* **Install Drivers:** Install the specific drivers for the **LED Matrix** and the **OLED display**.
* **Pro-tip:** Test all components on a breadboard before final soldering to ensure everything works correctly.

### 2. Component Verification
Check that you have all the components shown in the schematic:
* **Processing:** Raspberry Pi + GPIO Expansion Shield.
* **Displays:** LED Matrix (Main Visualizer) and I2C OLED Screen.
* **Audio Input:** Audio Interface (AI) and I2S Microphone/Module.
* **Controls:** Potentiometers and Navigation switches.
* **Power:** Power Supply (PS), AC Socket, and Power Switch.
* **Connectors:** XLR, RCA, and Jack 6.35mm terminals.

### 3. Tools Required
Prepare the following tools for the assembly:
* **Soldering Station:** For the wiring between the Raspberry Pi, sensors, and connectors.
* **Acetone & Brush:** For chemically welding the 3D printed parts (ABS/ASA).
* **Heat Shrink Tubing:** To insulate the connections, especially the AC power lines (L/N).
* **Precision Screwdriver Set:** To secure the Raspberry Pi and the Power Supply to the internal mounts.

### 4. Safety Warning
* **High Voltage:** The assembly involves wiring a Power Supply (PS) directly to an AC Socket. **Ensure the device is unplugged** during the entire wiring process.
* **Ventilation:** Use acetone in a well-ventilated area to avoid inhaling fumes during the cage assembly.

---

## 3D CAGE
[3D Printed Parts Directory](https://github.com/2ME3Elektronika/25-26_AudioScope/tree/19ac5f9debe1980ef2535abc0a953aee821c8050/3D%20cage/3D%20printed%20parts)

Through the previously provided link, the necessary parts to assemble the box that will contain all the project components are available.

To join the required pieces, acetone was used as the bonding agent.

---

## COMPONENT ASSEMBLY 
Once the cage is complete, the next step is to assemble all the components in the link below.

[Material List](https://github.com/2ME3Elektronika/25-26_AudioScope/tree/4716233cc459483782bc5c3bb550349c5cebfe78/Material)

To facilitate the examination of material connections, the following schematic diagram has been developed:

![image alt](https://github.com/2ME3Elektronika/25-26_AudioScope/blob/d882f9ad49f3fb111c56b66cdc975c31f51cb3b2/Schematics/Material%20connections.png)

To create the PCB that will enable the connection of all components, the following schematic has been developed:

[AudioScope PCB Project](https://github.com/2ME3Elektronika/25-26_AudioScope/blob/c6339670a8648a26b4ef2825f532ce45a1cc3c00/Schematics/AudioScope%20PCB.pdsprj)

To see the needed materials, the following directory has been developed:

[Full Materials Directory](https://github.com/2ME3Elektronika/25-26_AudioScope/tree/c6339670a8648a26b4ef2825f532ce45a1cc3c00/Material)
























# STEPS TO ASSEMBLY THE AUDIOSCOPE

## PRE-ASSEMBLY & PREPARATION
Before starting the physical construction, ensure you have completed these essential preparatory steps:

### 1. Software Configuration
It is highly recommended to configure the "brain" of the project before mounting it in the cage:
* **Flash the OS:** Install Raspbian (Lite version recommended) on your SD card.
* **Enable Interfaces:** Use `raspi-config` to enable **I2C** (for the OLED and sensors) and **I2S** (for the audio input).
* **Install Libraries:** Pre-install the drivers for the LED Matrix and the visualizer software to test components individually.

### 2. Safety & Tools
* **Soldering:** You will need a soldering station, solder, and heat shrink tubing to insulate the AC connections (L/N).
* **Chemical Bonding:** Ensure you have **Acetone** and a small brush if you are using ABS/ASA for the 3D parts.
* **Safety Warning:** This project involves **High Voltage (AC)**. Always disconnect the power supply from the wall before handling internal wiring.

---

## 3D CAGE
[3D Printed Parts Directory](https://github.com/2ME3Elektronika/25-26_AudioScope/tree/19ac5f9debe1980ef2535abc0a953aee821c8050/3D%20cage/3D%20printed%20parts)

Through the previously provided link, the necessary parts to assemble the box that will contain all the project components are available.

To join the required pieces, acetone was used as the bonding agent.

---

## COMPONENT ASSEMBLY 
Once the cage is complete, the next step is to assemble all the components in the link below.

[Material List](https://github.com/2ME3Elektronika/25-26_AudioScope/tree/4716233cc459483782bc5c3bb550349c5cebfe78/Material)

To facilitate the examination of material connections, the following schematic diagram has been developed.

![image alt](https://github.com/2ME3Elektronika/25-26_AudioScope/blob/d882f9ad49f3fb111c56b66cdc975c31f51cb3b2/Schematics/Material%20connections.png)

To create the PCB that will enable the connection of all components, the following schematic has been developed.

[AudioScope PCB Project](https://github.com/2ME3Elektronika/25-26_AudioScope/blob/c6339670a8648a26b4ef2825f532ce45a1cc3c00/Schematics/AudioScope%20PCB.pdsprj)

To see the needed materials, the following directory has been developed.

[Full Materials Directory](https://github.com/2ME3Elektronika/25-26_AudioScope/tree/c6339670a8648a26b4ef2825f532ce45a1cc3c00/Material)

## 3D CAGE
(https://github.com/2ME3Elektronika/25-26_AudioScope/tree/19ac5f9debe1980ef2535abc0a953aee821c8050/3D%20cage/3D%20printed%20parts)

Through the previously provided link, the necessary parts to assemble the box that will contain all the project components are available.

To join the required pieces, acetone was used as the bonding agent.

## COMPONENT ASSEMBLY 
Once the cage is complete, the next step is to assemble all the components in the link below.

(https://github.com/2ME3Elektronika/25-26_AudioScope/tree/4716233cc459483782bc5c3bb550349c5cebfe78/Material)

To facilitate the examination of material connections, the following schematic diagram has been developed.

![image alt](https://github.com/2ME3Elektronika/25-26_AudioScope/blob/d882f9ad49f3fb111c56b66cdc975c31f51cb3b2/Schematics/Material%20connections.png)

To create the PCB that will enable the connection of all components, the following schematic has been developed.

(https://github.com/2ME3Elektronika/25-26_AudioScope/blob/c6339670a8648a26b4ef2825f532ce45a1cc3c00/Schematics/AudioScope%20PCB.pdsprj)

To see the needed materials, the following directory has been developed.

(https://github.com/2ME3Elektronika/25-26_AudioScope/tree/c6339670a8648a26b4ef2825f532ce45a1cc3c00/Material)
