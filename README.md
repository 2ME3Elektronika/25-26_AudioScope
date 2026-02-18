# 💡 Idea of the project
A professional DIY project for real-time audio frequency spectrum visualization (20Hz-20KHz) using Raspberry Pi 4, Adafruit RGB Matrix HAT, and 64x64 RGB LED Matrix.

![Python](https://img.shields.io/badge/python-3.7+-blue)
![Platform](https://img.shields.io/badge/platform-Raspberry%20Pi%204%20Model%20B-green)
# Characteristics
- Visualizes frequencies from **20Hz-20kHz**.
- **Multiple** available imputs (Jack, RCA, ...).
- **Microphone** to test that the visualizer works.
- **Oled I2C display** with multiple functions.
# What is a **RGB matrix 64x64**
The **GRB Matrix 64x64** is an LED matrix display that allows images, animations, and text to be shown in a colorful and dynamic way. Its main features include:

![image alt](https://github.com/2ME3Elektronika/25-26_AudioScope/blob/71412fbe5fdc24284c8d4521987de8dd2542fbf4/Material/RGB%20matrix%2064x64%20P3.png)
- **64x64 LED matrix:** Composed of 64 rows and 64 columns, totaling 4096 individual LEDs.
- **GRB color format:** Each LED is RGB (Red, Green, Blue), but the color data is sent in Green → Red → Blue order, ensuring colors display correctly.
- **Microcontroller control:** Can be driven with boards like Arduino or Raspberry Pi using specific matrix drivers such as Hub75.
- **High display capability:** Suitable for showing graphics, animations, and text in real time.
- **Standard protocol compatibility:** Allows efficient color data transfer and matrix synchronization.

In this project, the GRB Matrix 64x64 is responsible for displaying a **frequency** into a animated **FFT**, working together with the microcontroller that manages the system logic.

# Hardware 
Here’s a link to the guide for all the hardware you’ll need for this project

(https://github.com/2ME3Elektronika/25-26_AudioScope/blob/5edb63df820f065019aefbd5968ed1fb7cb71b74/HARDWARE.md)

# Installation Guide
Here is a guide to follow step by step how we carried out all the processes on the Raspberry Pi

(https://github.com/2ME3Elektronika/25-26_AudioScope/blob/86c601f15b41f4d701bf3a58f58d1a194f8c7cf7/INSTALL.md)

# How To Use It?
1. Conect the power supply cable to a plug.
2. Click the power on **Button**.
3. Select the option you want to use with the **Rotary Encoder**.

Depending of the option you choose there are two routes.

## Microphone test mode
If you chose the **Microphone Test Mode**:

4. Talk to the microphone.
5. See if the display is showing the voice frequencies into FFT.

## Amplifier Test Mode
If you chose the **Amplifier Test Mode**:

4. Insert the output of the amplifier into of the inputs of the AudioScope.
5. See if the display is showing the frequencies into FFT.

# Preview Of The Project

<img width="500" height="500" alt="Gemini_Generated_Image_q8y5mxq8y5mxq8y5" src="https://github.com/user-attachments/assets/55f6d91c-b547-4185-a50f-ec43b5f62041" />
.
<img width="500" height="500" alt="c96424af-a062-4ec9-849e-a771dd6d81b2aaaaa" src="https://github.com/user-attachments/assets/a4fe83ec-756d-4063-8d14-ef46db5ed314" />


