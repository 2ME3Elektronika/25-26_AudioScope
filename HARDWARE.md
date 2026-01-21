# Hardware Requirements

### Core Components
1. **Raspberry Pi 4 Model B** (2GB or 4GB RAM recommended)

2. **Adafruit RGB Matrix HAT + RTC for Raspberry Pi**
   - Provides clean 5V power to LED matrix and level-shifted outputs

3. **64x64 RGB LED Matrix Panel - 3mm Pitch**
   - 3mm pitch recommended for better resolution
  
4. **5V 4A (4000mA) Power Supply**
   - For powering the LED matrix
   - Minimum 4A for full brightness on 64x64 matrix


## Power Considerations
### Power Budget
- Raspberry Pi 4: ~3W (600mA @ 5V)
- RGB Matrix HAT: ~0.5W (100mA @ 5V)
- 64x64 LED Matrix (full white): ~20W (4000mA @ 5V)
- 64x64 LED Matrix (typical usage): ~10W (2000mA @ 5V)
- LCD Display: ~0.5W (100mA @ 5V)
- USB Audio Interface: ~0.5W (100mA @ 5V)

Total: ~15W typical, ~25W maximum

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
