# 24-and-60-GHz-Radar-Sensors

Millimeter wave (mmWave) radar employs electromagnetic waves within the millimeter-wave band, ranging frequencies from 30 to 300 GHz. It offers numerous benefits compared to alternative radar types, such as enhanced resolution, deep penetration capabilities, and minimal interference. These advantages render mmWave radar highly suitable for diverse applications spanning automotive, security, and manufacturing sectors.

As a source material the data sheet of the two sensors was used. 
As result it appears that each band has its own advantages and disadvantages. 24 GHz radar has better penetration and range than 60 GHz radar, but it has lower resolution. 60 GHz radar has higher resolution than 24 GHz radar, but it has shorter range and worse penetration.
___________________________________________________________

The hardware system design for the 24 GHz mmWave Radar includes:
•	 24 GHz mmWave radar sensor
•	 Seeed XIAO BLE nRF52840
•	 2 LED (Red and Green) 
•	2 x 220Ω resistors. 
4.2	24GHz mmWave radar system 
The 24GHz mmWave radar is connected to the seeed XIAO BLE, and from the XIAO BLE connected to two resistors and LED’s as shown in figure 1 bellow.
 ![image](https://github.com/Roey8182/24-and-60-GHz-Radar-Sensors/assets/98890917/c455e963-10e4-422b-ba26-c2120d4c281b)

Figure 1. A Block diagram of the 24GHz mmWave radar system

![image](https://github.com/Roey8182/24-and-60-GHz-Radar-Sensors/assets/98890917/aab81eab-019d-4a8c-90aa-bbbb1c5a9f8b)
Figure 2. A wiring diagram of the 24GHz mmWave radar and the seeed XIAO BLE nRF52840

The wiring of the 60GHz mmWave radar and the seeed XIAO BLE is as shown below
![image](https://github.com/Roey8182/24-and-60-GHz-Radar-Sensors/assets/98890917/cbf6c55c-565c-43f3-b3b5-982628ba7130)

Wiring instructions
Seeed Studio XIAO 	Sensor 60GHz
5V      	--       5V
GND	      --       GND
RX       	--       D6
TX       	--       D7
