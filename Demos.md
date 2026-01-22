To be able of running some demos we decided to use the next website
(https://learn.adafruit.com/adafruit-rgb-matrix-plus-real-time-clock-hat-for-raspberry-pi/install-manually)

To see if our 64x64 rgb led matrix the next library can be used to see some demos.
-     git clone https://github.com/hzeller/rpi-rgb-led-matrix.git  cd rpi-rgb-led-matrix  make

Once you´re inside of the examples-api-use subdirectory the next code can be used to prove some examples. By changing the number at the end of the code(0-9) different samples can be put on the 64x64 matrix
-     sudo ./demo -D 0

If you encounter an image problem when running the demo, you should open the demo.py file located in the examples-api-use subdirectory and find the two lines that say rows and columns and change them from 32 to 64.
