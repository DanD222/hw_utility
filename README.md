# Hardware_STM32F4Discovery_Piggyback
Soaring Vario Hardware Design for audio Module. 

## Components
- STM32F4 Discovery Board
- PAM8302AAS  Audio Amplifier connected to STM32F4 DAC output
- 2 pin Screwterminal for loudspeaker
- RJ45 connector to external LED module to display actual and desired flaps postion. 
- RJ45 connector for CAN Interface
- 3.3V CAN Transceiver 
- RJ12 connector for external I2C sensor.  Input ESD potection required?
- RJ12 connector for air brakes, gear, flaps switch and one analog input.   How to protect these inputs? 
- 9 to 30V DC DC power supply.   LV2842XLVDDCR ?

- SD103AW  Schottky Barrier Diodes?




## One concept
- Bluepill
- 5V DC-DC 
- Audio external
- 30mV Peak Peak Ausschlag.   ?? 



PWM1 - 10k - | 
PWM2 - 10k - |  ---- |------ | ----- | ------|- > Audio Verstärker
					1k		2k		4k		8k
			   		|		|		|        |
					PB1		PB2		PB3      PB4    => Either set low or floating. 
					
Welche PINS wurden verwendet?