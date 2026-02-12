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

# How To Use It?
1. Click the power on **Button**.
2. Select the option you want to use with the **Rotary Encoder** .
3. a
4. a
   
# Preview Of The Project
<img width="384" height="256" alt="ChatGPT Image 19 ene 2026, 12_48_54" src="https://github.com/user-attachments/assets/d82ba941-ecb5-4d3a-a141-7b1822174d4a" />
<img width="512" height="341" alt="ChatGPT Image 19 ene 2026, 12_45_58_232" src="https://github.com/user-attachments/assets/ea44736c-96c5-456b-b503-1737deb8a6b3" />
