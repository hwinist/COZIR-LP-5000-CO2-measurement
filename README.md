The target of this project is long-term CO2 measurement in a closed container with limited space and limited power supply.
Due to the given restrictions (space, power supply, wireless operation), I chose the folllowing hardware components:
- Tinypico, a ESP32 development board by Unexpected Maker: https://www.tinypico.com/
- CozIR®-LP 5000 CO2 Sensor by GSS: https://www.co2meter.com/products/cozir-lp-ambient-air-co2-sensor

I have decided to use Micropython on Thonny 4.1.4.
My challenge: I am completely new to programming and am learning on the project.
The key resources are the Micropython documentation (https://docs.micropython.org/en/latest/micropython-docs.pdf), similar projects documented on github, forums and guidance on https://www.elektronik-kompendium.de/ .

The test operation with a 600mAh 3.7V Li-po battery and a reduced time between mesurements of 1h showed a battery capacity of >72h. Extrapolated to daily measurements instead, a total measurement period of two month at least can be achieved.
