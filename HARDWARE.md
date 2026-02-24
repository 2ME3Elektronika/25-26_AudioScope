#  Hardware Requirements

### Core Components
  1. **Raspberry Pi 4 Model B** (2GB or 4GB RAM recommended)

  2. **Adafruit RGB Matrix HAT + RTC for Raspberry Pi**
     - Provides clean 5V power to LED matrix and level-shifted outputs

  4. **64x64 RGB LED Matrix Panel - 3mm Pitch**
      - 3mm pitch recommended for better resolution
  
  5. **5V 4A (4000mA) Power Supply**
      - For powering the LED matrix
      - Minimum 4A for full brightness on 64x64 matrix

### Audio Input Hardware

### For Low-Level Signals (10mV-1V)
 **ADS1115 16-Bit ADC**
   - 4-channel, 16-bit resolution
   - I2C interface
   - Programmable gain amplifier (PGA)
   - Adafruit Product ID: 1085 or compatible

 **Input Protection Circuit Components:**
   - 1x Voltage divider resistors (10kΩ and 1kΩ)
   - 1x Capacitor 10µF (DC blocking)
   - 1x Op-amp (optional): TL072 or similar for signal conditioning
   - 2x Zener diodes 3.3V (input protection)
   - BNC or 3.5mm jack connector

### For High-Power Audio (40W Output)
#### USB Audio Interface
   - Any USB audio interface compatible with Raspberry Pi
   - Recommended: Behringer UCA202 or similar
   - Line-level input capability

** Voltage Divider/Attenuator Circuit:**
   - Resistors: 100kΩ and 10kΩ (10:1 attenuation)
   - Capacitor: 100µF (power supply decoupling)
   - Heat-shrink tubing or enclosure
   - Speaker wire connectors
     
#### Menu/Display Components
**Character LCD 20x4 with I2C backpack** OR **128x64 OLED Display**
   - For menu system and settings display
   - I2C interface preferred for easy connection
   - Options:
     - HD44780-compatible 20x4 LCD (recommended)
     - SSD1306 128x64 OLED display

## Power Considerations

### Power Budget
- Raspberry Pi 4: ~3W (600mA @ 5V)
- RGB Matrix HAT: ~0.5W (100mA @ 5V)
- 64x64 LED Matrix (full white): ~20W (4000mA @ 5V)
- 64x64 LED Matrix (typical usage): ~10W (2000mA @ 5V)
- LCD Display: ~0.5W (100mA @ 5V)
- USB Audio Interface: ~0.5W (100mA @ 5V)

**Total:** ~15W typical, ~25W maximum

## Power Supply Recommendations
- Use separate 5V 4A supply for LED matrix (via RGB Matrix HAT)
- Raspberry Pi can be powered from HAT's barrel jack
- Or use official Raspberry Pi 15W USB-C power supply
  
## Safety Notes
- Never exceed voltage ratings
- Use fuses on all power inputs
- Ensure proper grounding
- Keep high-power audio circuit isolated
- Use insulated connectors and enclosures
