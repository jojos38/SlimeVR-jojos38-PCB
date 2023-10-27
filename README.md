# SlimeVR-jojos38-PCB
A custom and fully featured PCB to make your own SlimeVR trackers!

### I am not taking any responsibility regarding this board, this includes but is not limited to: Board not working after order, missing or misbehaving features, any physical damage caused by the board and so on. Order this board at your own risk, do your own research and verifications if you have any doubt.

## Notes:
- The connector of the extension is a **JST ZH 1.5mm 5 PINS**
- If you want to use the battery temperature connector you will need to adjust the resistors on the PCB itself before ordering it
- To adjust the battery charging speed it's just an addition, for example solder 0.25A and 1A and you'll have 1.25A charging speed

## It features:
- Ultra compact 38x38mm motherboard, perfect for 40mm batteries
- Autostop feature (the sensors will stop themselves after x minutes if they aren't used)
- Ultra efficient charger provides fast adjustable charge (from 0.25A to 1.75A with 0.25A increment adjustability)
- Ultra efficient buck-boost powering, providing more than 90% efficiency
- Compatible with all USB C cables
- Single USB C port for everything: Charging, flashing and SlimeVR configuration
- Two status LEDs, one for charging (green) and one for SlimeVR (orange)
- Compatible with almost all IMU including BNO's (**Untested but should work**)
- ESD protection for the USB and the power button
- Low heating while charging and working
- Ability to add temperature sensor for the battery (**Require modification of the PCB before ordering**)

## Updates
- V4.0: Initial release
- V4.1: Fixed USB ESD diode wiring

## Problems
- Nothing is perfect and this PCB makes no exception
- The LED placement is not perfect relative to the cables for the main sensor. The cables could go on top the LED and hide it, it could see some improvements
- The size of the board (38x38) makes it complicated to fit with some batteries
- The boards can be a bit expensive to produce (~7€ per board)
- The lack of reset button can be annoying during testing because you need to short a pin of the ESP if you want to reset the board which is not ideal

## Important note: The ESD diode schematic is WRONG by the person who made it, I should have fixed it on the new variant but it wasn't tested

![Motherboard image](https://i.ibb.co/j6M91H0/20231001-211224.jpg)

![Motherboard imaget](https://i.ibb.co/9gCWfX9/20230911-113325.jpg)

![Motherboard image](https://i.ibb.co/2k5ZD9w/20230911-195816.jpg)

![Motherboard image](https://i.ibb.co/G5KXVT2/20230911-195844.jpg)

![Motherboard schematics](https://i.ibb.co/XLVFTxS/Schematic-Slime-VR-2023-10-28.png)


