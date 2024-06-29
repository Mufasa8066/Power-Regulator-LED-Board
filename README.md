# Power Regulator + LED Shield PCB for Arduino UNO

After completing a comprehensive PCB Design Course provided by Altium, we have been assigned a project to apply and test our skills in practical PCB Design. For this project, we will be creating a Power Regulator LED Shield Board specifically designed for an Arduino UNO. This shield board will serve two primary functions:

1.**Voltage Step-Down from 12V to 5V DC:** The board will include a voltage regulator circuit to step down the input voltage from 12V to 5V DC, supplying the necessary power to the Arduino UNO safely and efficiently.
2. **Powering a Bank of LEDs in Parallel:** The board will provide a stable power supply to a bank of LEDs connected in parallel, ensuring consistent brightness and performance.

# Requirements
The functional requirements of the board are as follows:
- Receive power from a 12 V DC input
- Regulate power down to 5 V DC
- Deliver 12 V DC power to a bank of 2 LED lights in parallel
- Provide 5 V DC power to the main Arduino Uno board
- Provide enough current to power the Arduino and the LEDs
- Regulate power with at least 90% efficiency
- LEDs must be SMD parts with high power output (at least 10 W each)
- Power input connection is provided by standard 16 AWG wire
- Components must be placed only on the top layer
- Total board thickness must be standard thickness (approximately 62 mils)

Since the board will be mounted onto the Arduino UNO, its dimensions will be based on those of the UNO.
<img width="257" alt="image" src="https://github.com/Mufasa8066/Power-Regulator-LED-Board/assets/124084701/0262c669-6ec1-4f00-b4e2-86db8dbe03d6">


# Design

These are the schematics, made from Altium Designer's schematic editor:
<img width="515" alt="Sch" src="https://github.com/Mufasa8066/Power-Regulator-LED-Board/assets/124084701/975416a8-6499-4812-be27-9b1608f80a9b">

Below is the finalized version of the PCB Layout:

<img width="468" alt="W" src="https://github.com/Mufasa8066/Power-Regulator-LED-Board/assets/124084701/ac7ad3b4-6a0c-43c9-94fd-9eef09426d86">
<img width="502" alt="Bottom_Layer" src="https://github.com/Mufasa8066/Power-Regulator-LED-Board/assets/124084701/ba3b8e58-9634-499d-aa00-4ffcd75d2d3a">
<img width="515" alt="S" src="https://github.com/Mufasa8066/Power-Regulator-LED-Board/assets/124084701/d4854151-cb0e-49ee-a182-b0f3d00de75c">

Below is the finalized 3d view of the board:

<img width="515" alt="l" src="https://github.com/Mufasa8066/Power-Regulator-LED-Board/assets/124084701/8b44ca95-59f1-464d-b8fa-7827875a37c4">





