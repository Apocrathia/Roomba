# Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`define `[`ROOMBA_MASK_LED_NONE`](#Roomba_8h_1a35d82152096fae1faecc5762fa2236b7)            | Masks for LEDs in leds()
`define `[`ROOMBA_MASK_LED_PLAY`](#Roomba_8h_1a5583f3f78edfa2ca58c34b3f749a0b46)            | 
`define `[`ROOMBA_MASK_LED_ADVANCE`](#Roomba_8h_1a8b989bfd76d124a75be80074aa52af3f)            | 
`define `[`ROOMBA_MASK_DIGITAL_OUT_0`](#Roomba_8h_1a389acaf537697599ba7c0ccab39ed5cb)            | Masks for digitalOut()
`define `[`ROOMBA_MASK_DIGITAL_OUT_1`](#Roomba_8h_1a7e58bc76da48df7c03e80807221178e8)            | 
`define `[`ROOMBA_MASK_DIGITAL_OUT_2`](#Roomba_8h_1a928b17a86c9610b6bc08f6ee57d8c911)            | 
`define `[`ROOMBA_MASK_DRIVER_0`](#Roomba_8h_1a9de512e251350d2eb62e316ad088e1c3)            | Masks for drivers()
`define `[`ROOMBA_MASK_DRIVER_1`](#Roomba_8h_1ad3cafab34fe90e8ad32a53bb2a6a0add)            | 
`define `[`ROOMBA_MASK_DRIVER_2`](#Roomba_8h_1acdff6e8d83ad9d6e5f13a5242695f529)            | 
`define `[`ROOMBA_MASK_SIDE_BRUSH`](#Roomba_8h_1a9eae623044fd54e5cf16f0704818cd65)            | [Roomba](#classRoomba) only:
`define `[`ROOMBA_MASK_VACUUM`](#Roomba_8h_1aee236aed74a5ba50e7872419853c679b)            | 
`define `[`ROOMBA_MASK_MAIN_BRUSH`](#Roomba_8h_1af618ac0327d114ce7b5f1f8e1a8a161e)            | 
`define `[`ROOMBA_MASK_BUMP_RIGHT`](#Roomba_8h_1a79d64a88e283f730930e4e2a651fc5a8)            | Masks for bumps and wheedrops sensor packet id 7.
`define `[`ROOMBA_MASK_BUMP_LEFT`](#Roomba_8h_1a3a7e0314e5e3c1100beae723b214ede2)            | 
`define `[`ROOMBA_MASK_WHEELDROP_RIGHT`](#Roomba_8h_1ac904e45444aff8b75e951c30af23160a)            | 
`define `[`ROOMBA_MASK_WHEELDROP_LEFT`](#Roomba_8h_1a4ea096c706658b173d4818a970dee8a7)            | 
`define `[`ROOMBA_MASK_WHEELDROP_CASTER`](#Roomba_8h_1a07cffde1f55e0e41a6c2d08a871c0785)            | 
`define `[`ROOMBA_MASK_LD1`](#Roomba_8h_1ad09853d8ed3e164c4042fa45cb5e84ed)            | Masks for driver overcurrents Packet ID 13.
`define `[`ROOMBA_MASK_LD0`](#Roomba_8h_1af92bd4af9e232a987b54fcb20265ab81)            | 
`define `[`ROOMBA_MASK_LD2`](#Roomba_8h_1aaed38030da40a1bc0a12279df2df4ece)            | 
`define `[`ROOMBA_MASK_RIGHT_WHEEL`](#Roomba_8h_1a26c5a66878b9c083499a316940eb6a9e)            | 
`define `[`ROOMBA_MASK_LEFT_WHEEL`](#Roomba_8h_1a5c855dfdb4e8dc9dd8fcc5334fe5dc4c)            | 
`define `[`ROOMBA_MASK_BUTTON_PLAY`](#Roomba_8h_1a6cb6bf4aa7de59dae962c849d9eea4e2)            | Masks for buttons sensor packet ID 18 Create
`define `[`ROOMBA_MASK_BUTTON_ADVANCE`](#Roomba_8h_1a32ed03313305f375914c06040e144fa7)            | 
`define `[`ROOMBA_MASK_BUTTON_MAX`](#Roomba_8h_1ade3d83a086780b471bfdbb866611f74f)            | [Roomba](#classRoomba).
`define `[`ROOMBA_MASK_BUTTON_CLEAN`](#Roomba_8h_1a250f17c333a39b29913cba447c36c78a)            | 
`define `[`ROOMBA_MASK_BUTTON_SPOT`](#Roomba_8h_1ad6392ee4c096439597a5650ea539f1ee)            | 
`define `[`ROOMBA_MASK_BUTTON_POWER`](#Roomba_8h_1a4e5ea44d8e028e4564e5a1698a6793b2)            | 
`define `[`ROOMBA_MASK_DIGITAL_IN_0`](#Roomba_8h_1a8e9fb7d1549f1c5c93197c4685017102)            | Masks for digital inputs sensor packet ID 32.
`define `[`ROOMBA_MASK_DIGITAL_IN_1`](#Roomba_8h_1a35201c45f1454205226bd0c48d0f3f1d)            | 
`define `[`ROOMBA_MASK_DIGITAL_IN_2`](#Roomba_8h_1a73d9a1bba6191c96a1117f6f53b107db)            | 
`define `[`ROOMBA_MASK_DIGITAL_IN_3`](#Roomba_8h_1ac6f28cb6f769a15181e000e85e7aae42)            | 
`define `[`ROOMBA_MASK_DIGITAL_IN_DEVICE_DETECT`](#Roomba_8h_1ad1a7eba4b3fccc8279713c434d1ab4d0)            | 
`define `[`ROOMBA_MASK_INTERNAL_CHARGER`](#Roomba_8h_1a022f318701cbc071e46563e10e96c042)            | Masks for charging sources sensor packet ID 34.
`define `[`ROOMBA_MASK_HOME_BASE`](#Roomba_8h_1ad84fc23eb70fa41424f14748534110de)            | 
`define `[`ROOMBA_READ_TIMEOUT`](#Roomba_8h_1ad36424bc1fecc12e9eadbd900e4f3315)            | Read timeout in milliseconds. If we have to wait more than this to read a char when we are expecting one, then something is wrong.
`class `[`Roomba`](#classRoomba) | Support for iRobot [Roomba](#classRoomba) and Create platforms via serial port using the iRobot Open Interface (OI) protocol.

## Members

#### `define `[`ROOMBA_MASK_LED_NONE`](#Roomba_8h_1a35d82152096fae1faecc5762fa2236b7) 

Masks for LEDs in leds()

#### `define `[`ROOMBA_MASK_LED_PLAY`](#Roomba_8h_1a5583f3f78edfa2ca58c34b3f749a0b46) 

#### `define `[`ROOMBA_MASK_LED_ADVANCE`](#Roomba_8h_1a8b989bfd76d124a75be80074aa52af3f) 

#### `define `[`ROOMBA_MASK_DIGITAL_OUT_0`](#Roomba_8h_1a389acaf537697599ba7c0ccab39ed5cb) 

Masks for digitalOut()

#### `define `[`ROOMBA_MASK_DIGITAL_OUT_1`](#Roomba_8h_1a7e58bc76da48df7c03e80807221178e8) 

#### `define `[`ROOMBA_MASK_DIGITAL_OUT_2`](#Roomba_8h_1a928b17a86c9610b6bc08f6ee57d8c911) 

#### `define `[`ROOMBA_MASK_DRIVER_0`](#Roomba_8h_1a9de512e251350d2eb62e316ad088e1c3) 

Masks for drivers()

#### `define `[`ROOMBA_MASK_DRIVER_1`](#Roomba_8h_1ad3cafab34fe90e8ad32a53bb2a6a0add) 

#### `define `[`ROOMBA_MASK_DRIVER_2`](#Roomba_8h_1acdff6e8d83ad9d6e5f13a5242695f529) 

#### `define `[`ROOMBA_MASK_SIDE_BRUSH`](#Roomba_8h_1a9eae623044fd54e5cf16f0704818cd65) 

[Roomba](#classRoomba) only:

#### `define `[`ROOMBA_MASK_VACUUM`](#Roomba_8h_1aee236aed74a5ba50e7872419853c679b) 

#### `define `[`ROOMBA_MASK_MAIN_BRUSH`](#Roomba_8h_1af618ac0327d114ce7b5f1f8e1a8a161e) 

#### `define `[`ROOMBA_MASK_BUMP_RIGHT`](#Roomba_8h_1a79d64a88e283f730930e4e2a651fc5a8) 

Masks for bumps and wheedrops sensor packet id 7.

#### `define `[`ROOMBA_MASK_BUMP_LEFT`](#Roomba_8h_1a3a7e0314e5e3c1100beae723b214ede2) 

#### `define `[`ROOMBA_MASK_WHEELDROP_RIGHT`](#Roomba_8h_1ac904e45444aff8b75e951c30af23160a) 

#### `define `[`ROOMBA_MASK_WHEELDROP_LEFT`](#Roomba_8h_1a4ea096c706658b173d4818a970dee8a7) 

#### `define `[`ROOMBA_MASK_WHEELDROP_CASTER`](#Roomba_8h_1a07cffde1f55e0e41a6c2d08a871c0785) 

#### `define `[`ROOMBA_MASK_LD1`](#Roomba_8h_1ad09853d8ed3e164c4042fa45cb5e84ed) 

Masks for driver overcurrents Packet ID 13.

#### `define `[`ROOMBA_MASK_LD0`](#Roomba_8h_1af92bd4af9e232a987b54fcb20265ab81) 

#### `define `[`ROOMBA_MASK_LD2`](#Roomba_8h_1aaed38030da40a1bc0a12279df2df4ece) 

#### `define `[`ROOMBA_MASK_RIGHT_WHEEL`](#Roomba_8h_1a26c5a66878b9c083499a316940eb6a9e) 

#### `define `[`ROOMBA_MASK_LEFT_WHEEL`](#Roomba_8h_1a5c855dfdb4e8dc9dd8fcc5334fe5dc4c) 

#### `define `[`ROOMBA_MASK_BUTTON_PLAY`](#Roomba_8h_1a6cb6bf4aa7de59dae962c849d9eea4e2) 

Masks for buttons sensor packet ID 18 Create

#### `define `[`ROOMBA_MASK_BUTTON_ADVANCE`](#Roomba_8h_1a32ed03313305f375914c06040e144fa7) 

#### `define `[`ROOMBA_MASK_BUTTON_MAX`](#Roomba_8h_1ade3d83a086780b471bfdbb866611f74f) 

[Roomba](#classRoomba).

#### `define `[`ROOMBA_MASK_BUTTON_CLEAN`](#Roomba_8h_1a250f17c333a39b29913cba447c36c78a) 

#### `define `[`ROOMBA_MASK_BUTTON_SPOT`](#Roomba_8h_1ad6392ee4c096439597a5650ea539f1ee) 

#### `define `[`ROOMBA_MASK_BUTTON_POWER`](#Roomba_8h_1a4e5ea44d8e028e4564e5a1698a6793b2) 

#### `define `[`ROOMBA_MASK_DIGITAL_IN_0`](#Roomba_8h_1a8e9fb7d1549f1c5c93197c4685017102) 

Masks for digital inputs sensor packet ID 32.

#### `define `[`ROOMBA_MASK_DIGITAL_IN_1`](#Roomba_8h_1a35201c45f1454205226bd0c48d0f3f1d) 

#### `define `[`ROOMBA_MASK_DIGITAL_IN_2`](#Roomba_8h_1a73d9a1bba6191c96a1117f6f53b107db) 

#### `define `[`ROOMBA_MASK_DIGITAL_IN_3`](#Roomba_8h_1ac6f28cb6f769a15181e000e85e7aae42) 

#### `define `[`ROOMBA_MASK_DIGITAL_IN_DEVICE_DETECT`](#Roomba_8h_1ad1a7eba4b3fccc8279713c434d1ab4d0) 

#### `define `[`ROOMBA_MASK_INTERNAL_CHARGER`](#Roomba_8h_1a022f318701cbc071e46563e10e96c042) 

Masks for charging sources sensor packet ID 34.

#### `define `[`ROOMBA_MASK_HOME_BASE`](#Roomba_8h_1ad84fc23eb70fa41424f14748534110de) 

#### `define `[`ROOMBA_READ_TIMEOUT`](#Roomba_8h_1ad36424bc1fecc12e9eadbd900e4f3315) 

Read timeout in milliseconds. If we have to wait more than this to read a char when we are expecting one, then something is wrong.

# class `Roomba` 

Support for iRobot [Roomba](#classRoomba) and Create platforms via serial port using the iRobot Open Interface (OI) protocol.

The iRobot [Roomba](#classRoomba) and Create platforms support a serial port through which you can control and interrogate the device. The protocol implemented here conforms to the Open Interface protocol described in the iRobot Open Interface Command Reference. Not all commands are supported on both platforms. Differences are noted in the API

The [Roomba](#classRoomba) and Create is equipped with a min-din serial port socket, while the Create is also equipped with a 25-pin D connector called the Cargo Bay Connector. The pins on the Cargo Bay Connector include the serial port, battery, digital inputs and outputs, and an analog input.

In order to communicate with a [Roomba](#classRoomba), you must create an instance of the [Roomba](#classRoomba) class and then call its instance methods to send commmands and receive sensor messages. You can also request continuous streams of sensor data to be sent by the [Roomba](#classRoomba). The [Roomba](#classRoomba) also emits messages on its serial port from time to time as described below.

Electrical Considerations

The serial port output TXD from the Roomba/Create is too weak to drive the RX serial port input of an Arduino properly. This is because of the USB-Serial converter on the Arduino: it also tries to drive the RX serial port input via a pullup resistor, but the [Roomba](#classRoomba) does not have enough drive to pull the RX down below about 2.5 volts, which is insufficient to be reliably detected as a TTL serial input of 0.

Note that this problem does not affect the Serial1 Serial2 or Serial3 ports on the Mega: these ports do not have other circuitry connected to them and the [Roomba](#classRoomba) can drive the serial port inputs of these ports without a problem. Its only the RX Serial port (ie the first Serial port) that is affected by this problem.

What this means is that if you intend to connect a [Roomba](#classRoomba) to the standard (first) RX/TX serial port on an Arduino you *MUST* have additional circuitry to help drive RX on the Arduino low enough. We use a simple PNP emitter follower. Almost any small signal low power PNP will do. See the [example circuit diagram](Create-Arduino.pdf). This will ensure the RX serial port input on the Arduino is pulled down to about 0.6V for reliable comms.

Other Roomba messages

When iRobot Create powers up and after a reset, it sends a message like this on its serial port: 
```cpp
bl-start
2006-09-12-1137-L   
RDK by iRobot!
MC9S12E128
2006-11-20-1731-L   
battery-current-quiescent-raw 524  battery-current-zero 510

2006-11-20-1731-L   
```

While charging it will send a message like this each second: 
```cpp
bat:   min 3  sec 21  mV 15558  mA 1491  deg-C 24  
```

To enter the factory test menu for the IRobot Create, hold down the (>) and (>>|) buttons then press and hold the Power button until the assending and descending tones play and then stop. You wil see some messages emitted on teh serial port. Press the right-right arrow button to cycle through the tests.

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public  `[`Roomba`](#classRoomba_1af56b83b2821da8dc6300d4d2480c9923)`(HardwareSerial * serial,`[`Baud`](#classRoomba_1a5db4cc6d2611406473511c7633e01611)` baud)` | Constructor. You can have multiple simultaneous [Roomba](#classRoomba) if that makes sense. 
`public void `[`reset`](#classRoomba_1ae15fd66f9c3b1583929c9940991329f5)`()` | Resets the [Roomba](#classRoomba). It will emit its startup message Caution, this may take several seconds to complete
`public void `[`start`](#classRoomba_1ab3fb9440e1ecfbf8de17eb49de420607)`()` | Starts the Open Interface and sets the mode to Passive. You must send this before sending any other commands. Initialises the serial port to the baud rate given in the constructor
`public uint32_t `[`baudCodeToBaudRate`](#classRoomba_1ae77368d84e06dc9212b769b5e29ba995)`(`[`Baud`](#classRoomba_1a5db4cc6d2611406473511c7633e01611)` baud)` | Converts the specified baud code into a baud rate in bits per second 
`public void `[`baud`](#classRoomba_1a452047d0b88077c1cee8a458ff9cbb6e)`(`[`Baud`](#classRoomba_1a5db4cc6d2611406473511c7633e01611)` baud)` | Changes the baud rate Baud is on of the [Roomba::Baud](#classRoomba_1a5db4cc6d2611406473511c7633e01611) enums
`public void `[`safeMode`](#classRoomba_1a1e979990f9b3c695e8149ca6959a56b7)`()` | Sets the OI to Safe mode. In Safe mode, the cliff and wheel drop detectors work to prevent [Roomba](#classRoomba) driving off a cliff
`public void `[`fullMode`](#classRoomba_1aabf3f21afc9ee580427f8337bccd4627)`()` | Sets the OI to Full mode. In Full mode, the cliff and wheel drop detectors do not stop the motors: you are responsible
`public void `[`power`](#classRoomba_1acba244fafd5894b28fda6b8322a62857)`()` | Puts a [Roomba](#classRoomba) in sleep mode. [Roomba](#classRoomba) only, no equivalent for Create.
`public void `[`dock`](#classRoomba_1a6f7633bedad09de99bcad156a11c0ba3)`()` | Causes roomba to immediately seek the docking station. No equivalent for Create.
`public void `[`demo`](#classRoomba_1ae6884b116088ec02f197ae764405e62f)`(`[`Demo`](#classRoomba_1a85c87c27f29d9eb6e01ce96a91cebd4e)` demo)` | Starts the requirested built-in demo 
`public void `[`cover`](#classRoomba_1a621c4b2e58183d857700f64b4bfec273)`()` | Starts the Cover demo Changes mode to Passive
`public void `[`coverAndDock`](#classRoomba_1a8fb028ca9cc211c0b929eef00b156f5b)`()` | Starts the Cover and Dock demo Changes mode to Passive
`public void `[`spot`](#classRoomba_1a84b0b1e6d8de23a7898e594c92d9fdc6)`()` | Starts the Spot Cover demo Changes mode to Passive
`public void `[`drive`](#classRoomba_1ab69511e88b7176c550d0cd55a1547a53)`(int16_t velocity,int16_t radius)` | Starts the [Roomba](#classRoomba) driving with a specified wheel velocity and radius of turn 
`public void `[`driveDirect`](#classRoomba_1ade2d3b8a87e5194257299db39eb1a04a)`(int16_t leftVelocity,int16_t rightVelocity)` | Starts the [Roomba](#classRoomba) driving with a specified velocity for each wheel Create only. No equivalent on [Roomba](#classRoomba). 
`public void `[`leds`](#classRoomba_1afa4be222e6576d405f4046470435794b)`(uint8_t leds,uint8_t powerColour,uint8_t powerIntensity)` | Controls the LEDs on the Create 
`public void `[`digitalOut`](#classRoomba_1ac3a9b25f5d4d4f220aa6522385d15de6)`(uint8_t out)` | Sets the digital output pins on the Cargo Bay Connector of the Create Create only. No equivalent on [Roomba](#classRoomba). 
`public void `[`pwmDrivers`](#classRoomba_1a0880b6765abec586308b67e414bb92a2)`(uint8_t dutyCycle0,uint8_t dutyCycle1,uint8_t dutyCycle2)` | Sets the duty cycle for PWM outputs on the low side drivers. These can be use for PWM driving of motors, lights etc. Create only. No equivalent on [Roomba](#classRoomba). 
`public void `[`drivers`](#classRoomba_1a4a77a7a203fb7f93b4ebdcfbb7f1283b)`(uint8_t out)` | Sets the low side drivers on or off. On the Romba, these control the 3 motors. 
`public void `[`sendIR`](#classRoomba_1a51bf88de0bca6f75c8f57c0e290cfe39)`(uint8_t data)` | Sends the requested byte out of the low side driver 1 (pin 23 on the Cargo Bay Connector). low side driver 1 can be used to drive an IR transmitter to send commands to other Roombas and Creates. Create only. No equivalent on [Roomba](#classRoomba). 
`public void `[`song`](#classRoomba_1a0665940c14c5253ec49c58ca42a2f68e)`(uint8_t songNumber,const uint8_t * notes,int len)` | Defines a song which can later be played with [playSong()](#classRoomba_1a45052b2b4d99892f49d6f5d959742f6a)
`public void `[`playSong`](#classRoomba_1a45052b2b4d99892f49d6f5d959742f6a)`(uint8_t songNumber)` | Plays a song that has previously been defined by [song()](#classRoomba_1a0665940c14c5253ec49c58ca42a2f68e)
`public void `[`stream`](#classRoomba_1aea5a0701342ac076aed60e400a6ac457)`(const uint8_t * packetIDs,int len)` | Requests that a stream of sensor data packets be sent by the [Roomba](#classRoomba). See the Open Interface manual for details on the resutting data. The packets will be sent every 15ms. You can use [pollSensors()](#classRoomba_1a72ad617937c2679c35d6c4b7a4663e52) to receive sensor data streams. Create only. No equivalent on [Roomba](#classRoomba). See the Open Interface maual for more details and limitations. 
`public void `[`streamCommand`](#classRoomba_1aea8864c72aa98210a3106dbafdc99594)`(`[`StreamCommand`](#classRoomba_1a430e6f03a756389adcc67762affbc43c)` command)` | Pause or resume a stream of sensor data packets previously requested by [stream()](#classRoomba_1aea5a0701342ac076aed60e400a6ac457) Create only. No equivalent on [Roomba](#classRoomba). 
`public void `[`script`](#classRoomba_1a5be3f8e1586340b63233271e643a3c1f)`(const uint8_t * script,uint8_t len)` | Defines a command script which can later be executed with [playScript()](#classRoomba_1a430fd32eec619a4b2dc0cee1acf39249). You can clear the script by calling script(NULL, 0); Create only. No equivalent on [Roomba](#classRoomba). 
`public void `[`playScript`](#classRoomba_1a430fd32eec619a4b2dc0cee1acf39249)`()` | Executes a previously defined script, the last one specified by [script()](#classRoomba_1a5be3f8e1586340b63233271e643a3c1f) Create only. No equivalent on [Roomba](#classRoomba).
`public void `[`wait`](#classRoomba_1ade1592e76c44dab3b49a244cdfafa0ad)`(uint8_t ticks)` | Tells the [Roomba](#classRoomba) to wait for a specified time. This command is intended for use in scripting only. Create only. No equivalent on [Roomba](#classRoomba). 
`public void `[`waitDistance`](#classRoomba_1a60ee60d4b089d5abedb42d4a2f530a8f)`(int16_t mm)` | Causes [Roomba](#classRoomba) to wait until it has travelled the distance specified. [Roomba](#classRoomba) will not react to any inputs until the wait has completed. Note that this does not cause the host arduino to wait, it only sends the wait comman to the [Roomba](#classRoomba) This command is intended for use in scripting only. Create only. No equivalent on [Roomba](#classRoomba). 
`public void `[`waitAngle`](#classRoomba_1a8f195735b87d928a9ae65aac991e1d7f)`(int16_t degrees)` | Causes [Roomba](#classRoomba) to wait until it has rotated through the specified angle. [Roomba](#classRoomba) will not react to any inputs until the wait has completed. Note that this does not cause the host arduino to wait, it only sends the wait comman to the [Roomba](#classRoomba) This command is intended for use in scripting only. Create only. No equivalent on [Roomba](#classRoomba). 
`public void `[`waitEvent`](#classRoomba_1a9c3bb7040c111c3a3467ecd4b17f0c52)`(`[`EventType`](#classRoomba_1abb4d3274e2698b8f1a670a590adc5c46)` type)` | Cause the Create to wait for a specified event. [Roomba](#classRoomba) will not react to any inputs until the wait has completed. Note that this does not cause the host arduino to wait, it only sends the wait comman to the [Roomba](#classRoomba) Create only. No equivalent on [Roomba](#classRoomba). 
`public bool `[`getData`](#classRoomba_1ad98352d87fa14057ed007f64886beee3)`(uint8_t * dest,uint8_t len)` | Low level funciton to read len bytes of data from the [Roomba](#classRoomba) Blocks untill all len bytes are read or a read timeout occurs. 
`public bool `[`getSensors`](#classRoomba_1a630c7bb65660c6d0199fec5d64bea465)`(uint8_t packetID,uint8_t * dest,uint8_t len)` | Reads the sensor data for the specified sensor packet ID. Note that different sensor packets have different lengths, and it is the callers responsibilty to make sure len agrees with the expected length of the sensor data. See the Open Interface manual for details on sensor packet lengths. [Roomba.h](#Roomba_8h_source) defines various enums and defines for decoding sensor data. Blocks untill all len bytes are read or a read timeout occurs. 
`public bool `[`getSensorsList`](#classRoomba_1adacd6f2271766b58c1e5211f8279c69b)`(uint8_t * packetIDs,uint8_t numPacketIDs,uint8_t * dest,uint8_t len)` | Reads the sensor data for the specified set of sensor packet IDs. Note that different sensor packets have different lengths, and it is the callers responsibilty to make sure len agrees with the expected length of the sensor data. See the Open Interface manual for details on sensor packet lengths. Blocks until all len bytes are read or a read timeout occurs. Create only. No equivalent on [Roomba](#classRoomba). 
`public bool `[`pollSensors`](#classRoomba_1a72ad617937c2679c35d6c4b7a4663e52)`(uint8_t * dest,uint8_t len)` | Polls the serial input for data belonging to a sensor data stream previously requested with [stream()](#classRoomba_1aea5a0701342ac076aed60e400a6ac457). As sensor data is read it is appended to dest until at most len bytes are stored there. When a complete sensor stream has been read with a correct checksum, returns true. See the Open Interface manual for details on how the sensor data will be encoded in dest. Discards characters that are not part of a stream, such as the messages the [Roomba](#classRoomba) sends at startup and while charging. Create only. No equivalent on [Roomba](#classRoomba). 
`public uint8_t `[`getScript`](#classRoomba_1a725fff9ebfa5a10b3040f56ed1d78a11)`(uint8_t * dest,uint8_t len)` | Reads a the contents of the script most recently specified by a call to [script()](#classRoomba_1a5be3f8e1586340b63233271e643a3c1f). Create only. No equivalent on [Roomba](#classRoomba). 
`enum `[`Baud`](#classRoomba_1a5db4cc6d2611406473511c7633e01611) | Demo types to pass to [Roomba::baud()](#classRoomba_1a452047d0b88077c1cee8a458ff9cbb6e)
`enum `[`Demo`](#classRoomba_1a85c87c27f29d9eb6e01ce96a91cebd4e) | Demo types to pass to [Roomba::demo()](#classRoomba_1ae6884b116088ec02f197ae764405e62f)
`enum `[`Drive`](#classRoomba_1a2e382956bcc02f04ffd3496f7a44e1c4) | Special values for radius in [Roomba::drive()](#classRoomba_1ab69511e88b7176c550d0cd55a1547a53)
`enum `[`StreamCommand`](#classRoomba_1a430e6f03a756389adcc67762affbc43c) | Values to pass to [Roomba::streamCommand()](#classRoomba_1aea8864c72aa98210a3106dbafdc99594)
`enum `[`EventType`](#classRoomba_1abb4d3274e2698b8f1a670a590adc5c46) | Values to pass to [Roomba::waitEvent()](#classRoomba_1a9c3bb7040c111c3a3467ecd4b17f0c52)
`enum `[`IRCommand`](#classRoomba_1a3d746bbb375be99981ad8ad8cb6c53f6) | Values for sensor packet ID 27
`enum `[`ChargeState`](#classRoomba_1ad3b677d855f55252417c538edb50d71f) | Values for sensor packet ID 21
`enum `[`Mode`](#classRoomba_1acd756c6947fcbce1df722b864a16b9cd) | Values for sensor packet ID 35
`enum `[`Sensor`](#classRoomba_1ae1a50282471bf1cf58c637851323054f) | Values for sensor packet IDs to pass to [getSensors()](#classRoomba_1a630c7bb65660c6d0199fec5d64bea465) and [getSensorsList()](#classRoomba_1adacd6f2271766b58c1e5211f8279c69b)

## Members

#### `public  `[`Roomba`](#classRoomba_1af56b83b2821da8dc6300d4d2480c9923)`(HardwareSerial * serial,`[`Baud`](#classRoomba_1a5db4cc6d2611406473511c7633e01611)` baud)` 

Constructor. You can have multiple simultaneous [Roomba](#classRoomba) if that makes sense. 
#### Parameters
* `serial` POinter to the HardwareSerial port to use to communicate with the [Roomba](#classRoomba). Defaults to &Serial 

* `baud` the baud rate to use on the serial port. Defaults to 57600, the default for the [Roomba](#classRoomba).

#### `public void `[`reset`](#classRoomba_1ae15fd66f9c3b1583929c9940991329f5)`()` 

Resets the [Roomba](#classRoomba). It will emit its startup message Caution, this may take several seconds to complete

#### `public void `[`start`](#classRoomba_1ab3fb9440e1ecfbf8de17eb49de420607)`()` 

Starts the Open Interface and sets the mode to Passive. You must send this before sending any other commands. Initialises the serial port to the baud rate given in the constructor

#### `public uint32_t `[`baudCodeToBaudRate`](#classRoomba_1ae77368d84e06dc9212b769b5e29ba995)`(`[`Baud`](#classRoomba_1a5db4cc6d2611406473511c7633e01611)` baud)` 

Converts the specified baud code into a baud rate in bits per second 
#### Parameters
* `baud` Baud code, one of [Roomba::Baud](#classRoomba_1a5db4cc6d2611406473511c7633e01611)

#### Returns
baud rate in bits per second

#### `public void `[`baud`](#classRoomba_1a452047d0b88077c1cee8a458ff9cbb6e)`(`[`Baud`](#classRoomba_1a5db4cc6d2611406473511c7633e01611)` baud)` 

Changes the baud rate Baud is on of the [Roomba::Baud](#classRoomba_1a5db4cc6d2611406473511c7633e01611) enums

#### `public void `[`safeMode`](#classRoomba_1a1e979990f9b3c695e8149ca6959a56b7)`()` 

Sets the OI to Safe mode. In Safe mode, the cliff and wheel drop detectors work to prevent [Roomba](#classRoomba) driving off a cliff

#### `public void `[`fullMode`](#classRoomba_1aabf3f21afc9ee580427f8337bccd4627)`()` 

Sets the OI to Full mode. In Full mode, the cliff and wheel drop detectors do not stop the motors: you are responsible

#### `public void `[`power`](#classRoomba_1acba244fafd5894b28fda6b8322a62857)`()` 

Puts a [Roomba](#classRoomba) in sleep mode. [Roomba](#classRoomba) only, no equivalent for Create.

#### `public void `[`dock`](#classRoomba_1a6f7633bedad09de99bcad156a11c0ba3)`()` 

Causes roomba to immediately seek the docking station. No equivalent for Create.

#### `public void `[`demo`](#classRoomba_1ae6884b116088ec02f197ae764405e62f)`(`[`Demo`](#classRoomba_1a85c87c27f29d9eb6e01ce96a91cebd4e)` demo)` 

Starts the requirested built-in demo 
#### Parameters
* `demo` The demo number. One of [Roomba::Demo](#classRoomba_1a85c87c27f29d9eb6e01ce96a91cebd4e)

#### `public void `[`cover`](#classRoomba_1a621c4b2e58183d857700f64b4bfec273)`()` 

Starts the Cover demo Changes mode to Passive

#### `public void `[`coverAndDock`](#classRoomba_1a8fb028ca9cc211c0b929eef00b156f5b)`()` 

Starts the Cover and Dock demo Changes mode to Passive

#### `public void `[`spot`](#classRoomba_1a84b0b1e6d8de23a7898e594c92d9fdc6)`()` 

Starts the Spot Cover demo Changes mode to Passive

#### `public void `[`drive`](#classRoomba_1ab69511e88b7176c550d0cd55a1547a53)`(int16_t velocity,int16_t radius)` 

Starts the [Roomba](#classRoomba) driving with a specified wheel velocity and radius of turn 
#### Parameters
* `velocity` Speed in mm/s (-500 to 500 mm/s) 

* `radius` Radius of the turn in mm. (-2000 to 2000 mm). Any of the special values in enum [Roomba::Drive](#classRoomba_1a2e382956bcc02f04ffd3496f7a44e1c4) may be used instead of a radius value

#### `public void `[`driveDirect`](#classRoomba_1ade2d3b8a87e5194257299db39eb1a04a)`(int16_t leftVelocity,int16_t rightVelocity)` 

Starts the [Roomba](#classRoomba) driving with a specified velocity for each wheel Create only. No equivalent on [Roomba](#classRoomba). 
#### Parameters
* `leftVelocity` Left wheel velocity in mm/s (-500 to 500 mm/s) 

* `rightVelocity` Right wheel velocity in mm/s (-500 to 500 mm/s)

#### `public void `[`leds`](#classRoomba_1afa4be222e6576d405f4046470435794b)`(uint8_t leds,uint8_t powerColour,uint8_t powerIntensity)` 

Controls the LEDs on the Create 
#### Parameters
* `leds` Bitmask specifying which LEDs to activate. ORed combination of ROOMBA_MASK_LED_* 

* `powerColour` The colour of the Power LED. 0 to 255. 0 = green, 255 = red, intermediate values are intermediate colours 

* `powerIntensity` Power LED intensity. 0 to 255. 0 = off, 255 = full intensity

#### `public void `[`digitalOut`](#classRoomba_1ac3a9b25f5d4d4f220aa6522385d15de6)`(uint8_t out)` 

Sets the digital output pins on the Cargo Bay Connector of the Create Create only. No equivalent on [Roomba](#classRoomba). 
#### Parameters
* `out` Mask specifiying which outputs to enable. ORed value ROOMBA_MASK_DIGITAL_OUT_*

#### `public void `[`pwmDrivers`](#classRoomba_1a0880b6765abec586308b67e414bb92a2)`(uint8_t dutyCycle0,uint8_t dutyCycle1,uint8_t dutyCycle2)` 

Sets the duty cycle for PWM outputs on the low side drivers. These can be use for PWM driving of motors, lights etc. Create only. No equivalent on [Roomba](#classRoomba). 
#### Parameters
* `dutyCycle0` Duty cycle for low side driver 0. 0 to 128. 

* `dutyCycle1` Duty cycle for low side driver 1. 0 to 128. 

* `dutyCycle2` Duty cycle for low side driver 2. 0 to 128.

#### `public void `[`drivers`](#classRoomba_1a4a77a7a203fb7f93b4ebdcfbb7f1283b)`(uint8_t out)` 

Sets the low side drivers on or off. On the Romba, these control the 3 motors. 
#### Parameters
* `out` Bitmask of putputs to enable. ORed value ROOMBA_MASK_DRIVER_*

#### `public void `[`sendIR`](#classRoomba_1a51bf88de0bca6f75c8f57c0e290cfe39)`(uint8_t data)` 

Sends the requested byte out of the low side driver 1 (pin 23 on the Cargo Bay Connector). low side driver 1 can be used to drive an IR transmitter to send commands to other Roombas and Creates. Create only. No equivalent on [Roomba](#classRoomba). 
#### Parameters
* `data` Data byte to transmit

#### `public void `[`song`](#classRoomba_1a0665940c14c5253ec49c58ca42a2f68e)`(uint8_t songNumber,const uint8_t * notes,int len)` 

Defines a song which can later be played with [playSong()](#classRoomba_1a45052b2b4d99892f49d6f5d959742f6a)
#### Parameters
* `songNumber` Song number for this song. 0 to 15 

* `notes` Array of note/duration pairs. See Open Interface manual for details. 2 bytes per note, first byte is the note and the second is the duration 

* `len` Length of notes array in bytes, so this will be twice the number of notes in the song

#### `public void `[`playSong`](#classRoomba_1a45052b2b4d99892f49d6f5d959742f6a)`(uint8_t songNumber)` 

Plays a song that has previously been defined by [song()](#classRoomba_1a0665940c14c5253ec49c58ca42a2f68e)
#### Parameters
* `songNumber` The song number to play. 0 to 15

#### `public void `[`stream`](#classRoomba_1aea5a0701342ac076aed60e400a6ac457)`(const uint8_t * packetIDs,int len)` 

Requests that a stream of sensor data packets be sent by the [Roomba](#classRoomba). See the Open Interface manual for details on the resutting data. The packets will be sent every 15ms. You can use [pollSensors()](#classRoomba_1a72ad617937c2679c35d6c4b7a4663e52) to receive sensor data streams. Create only. No equivalent on [Roomba](#classRoomba). See the Open Interface maual for more details and limitations. 
#### Parameters
* `packetIDs` Array specifying sensor packet IDs from [Roomba::Sensor](#classRoomba_1ae1a50282471bf1cf58c637851323054f) to be sent. 

* `len` Number of IDs in packetIDs

#### `public void `[`streamCommand`](#classRoomba_1aea8864c72aa98210a3106dbafdc99594)`(`[`StreamCommand`](#classRoomba_1a430e6f03a756389adcc67762affbc43c)` command)` 

Pause or resume a stream of sensor data packets previously requested by [stream()](#classRoomba_1aea5a0701342ac076aed60e400a6ac457) Create only. No equivalent on [Roomba](#classRoomba). 
#### Parameters
* `command` One of [Roomba::StreamCommand](#classRoomba_1a430e6f03a756389adcc67762affbc43c)

#### `public void `[`script`](#classRoomba_1a5be3f8e1586340b63233271e643a3c1f)`(const uint8_t * script,uint8_t len)` 

Defines a command script which can later be executed with [playScript()](#classRoomba_1a430fd32eec619a4b2dc0cee1acf39249). You can clear the script by calling script(NULL, 0); Create only. No equivalent on [Roomba](#classRoomba). 
#### Parameters
* `script` Array containing a sequence of [Roomba](#classRoomba) OI commands. 

* `len` Length of the script in bytes.

#### `public void `[`playScript`](#classRoomba_1a430fd32eec619a4b2dc0cee1acf39249)`()` 

Executes a previously defined script, the last one specified by [script()](#classRoomba_1a5be3f8e1586340b63233271e643a3c1f) Create only. No equivalent on [Roomba](#classRoomba).

#### `public void `[`wait`](#classRoomba_1ade1592e76c44dab3b49a244cdfafa0ad)`(uint8_t ticks)` 

Tells the [Roomba](#classRoomba) to wait for a specified time. This command is intended for use in scripting only. Create only. No equivalent on [Roomba](#classRoomba). 
#### Parameters
* `ticks` The number of ticks to wait. Each tick is 15ms

#### `public void `[`waitDistance`](#classRoomba_1a60ee60d4b089d5abedb42d4a2f530a8f)`(int16_t mm)` 

Causes [Roomba](#classRoomba) to wait until it has travelled the distance specified. [Roomba](#classRoomba) will not react to any inputs until the wait has completed. Note that this does not cause the host arduino to wait, it only sends the wait comman to the [Roomba](#classRoomba) This command is intended for use in scripting only. Create only. No equivalent on [Roomba](#classRoomba). 
#### Parameters
* `mm` Distance to wait for in mm

#### `public void `[`waitAngle`](#classRoomba_1a8f195735b87d928a9ae65aac991e1d7f)`(int16_t degrees)` 

Causes [Roomba](#classRoomba) to wait until it has rotated through the specified angle. [Roomba](#classRoomba) will not react to any inputs until the wait has completed. Note that this does not cause the host arduino to wait, it only sends the wait comman to the [Roomba](#classRoomba) This command is intended for use in scripting only. Create only. No equivalent on [Roomba](#classRoomba). 
#### Parameters
* `degrees` Angle to wait for in degrees

#### `public void `[`waitEvent`](#classRoomba_1a9c3bb7040c111c3a3467ecd4b17f0c52)`(`[`EventType`](#classRoomba_1abb4d3274e2698b8f1a670a590adc5c46)` type)` 

Cause the Create to wait for a specified event. [Roomba](#classRoomba) will not react to any inputs until the wait has completed. Note that this does not cause the host arduino to wait, it only sends the wait comman to the [Roomba](#classRoomba) Create only. No equivalent on [Roomba](#classRoomba). 
#### Parameters
* `type` Event type to wait for. One of [Roomba::EventType](#classRoomba_1abb4d3274e2698b8f1a670a590adc5c46)

#### `public bool `[`getData`](#classRoomba_1ad98352d87fa14057ed007f64886beee3)`(uint8_t * dest,uint8_t len)` 

Low level funciton to read len bytes of data from the [Roomba](#classRoomba) Blocks untill all len bytes are read or a read timeout occurs. 
#### Parameters
* `dest` Destination where the read data is stored. Must have at least len bytes available. 

* `len` Number of bytes to read 

#### Returns
true if all len bytes were successfully read. Returns false in the case of a timeout on reading any byte.

#### `public bool `[`getSensors`](#classRoomba_1a630c7bb65660c6d0199fec5d64bea465)`(uint8_t packetID,uint8_t * dest,uint8_t len)` 

Reads the sensor data for the specified sensor packet ID. Note that different sensor packets have different lengths, and it is the callers responsibilty to make sure len agrees with the expected length of the sensor data. See the Open Interface manual for details on sensor packet lengths. [Roomba.h](#Roomba_8h_source) defines various enums and defines for decoding sensor data. Blocks untill all len bytes are read or a read timeout occurs. 
#### Parameters
* `packetID` The ID of the sensor packet to read from [Roomba::Sensor](#classRoomba_1ae1a50282471bf1cf58c637851323054f)

* `dest` Destination where the read data is stored. Must have at least len bytes available. 

* `len` Number of sensor data bytes to read 

#### Returns
true if all len bytes were successfully read. Returns false in the case of a timeout on reading any byte.

#### `public bool `[`getSensorsList`](#classRoomba_1adacd6f2271766b58c1e5211f8279c69b)`(uint8_t * packetIDs,uint8_t numPacketIDs,uint8_t * dest,uint8_t len)` 

Reads the sensor data for the specified set of sensor packet IDs. Note that different sensor packets have different lengths, and it is the callers responsibilty to make sure len agrees with the expected length of the sensor data. See the Open Interface manual for details on sensor packet lengths. Blocks until all len bytes are read or a read timeout occurs. Create only. No equivalent on [Roomba](#classRoomba). 
#### Parameters
* `packetIDs` Array of IDs from [Roomba::Sensor](#classRoomba_1ae1a50282471bf1cf58c637851323054f) of the sensor packets to read 

* `numPacketIDs` number of IDs in the packetIDs array 

* `dest` Destination where the read data is stored. Must have at least len bytes available. 

* `len` Number of sensor data bytes to read and store to dest. 

#### Returns
true if all len bytes were successfully read. Returns false in the case of a timeout on reading any byte.

#### `public bool `[`pollSensors`](#classRoomba_1a72ad617937c2679c35d6c4b7a4663e52)`(uint8_t * dest,uint8_t len)` 

Polls the serial input for data belonging to a sensor data stream previously requested with [stream()](#classRoomba_1aea5a0701342ac076aed60e400a6ac457). As sensor data is read it is appended to dest until at most len bytes are stored there. When a complete sensor stream has been read with a correct checksum, returns true. See the Open Interface manual for details on how the sensor data will be encoded in dest. Discards characters that are not part of a stream, such as the messages the [Roomba](#classRoomba) sends at startup and while charging. Create only. No equivalent on [Roomba](#classRoomba). 
#### Parameters
* `dest` Destination where the read data is stored. Must have at least len bytes available. 

* `len` Max number of sensor data bytes to store to dest 

#### Returns
true when a complete stream has been read, and the checksum is correct. The sensor data (at most len bytes) will have been stored into dest, ready for the caller to decode.

#### `public uint8_t `[`getScript`](#classRoomba_1a725fff9ebfa5a10b3040f56ed1d78a11)`(uint8_t * dest,uint8_t len)` 

Reads a the contents of the script most recently specified by a call to [script()](#classRoomba_1a5be3f8e1586340b63233271e643a3c1f). Create only. No equivalent on [Roomba](#classRoomba). 
#### Parameters
* `dest` Destination where the read data is stored. Must have at least len bytes available. 

* `len` The maximum number of bytes to place in dest. If the script is actually longer than len only len bytes will be written 

#### Returns
The actual number of bytes in the script, even if this is more than len. By calling getScript(NULL, 0), you can determine how many bytes would be required to store the script.

#### `enum `[`Baud`](#classRoomba_1a5db4cc6d2611406473511c7633e01611) 

 Values                         | Descriptions                                
--------------------------------|---------------------------------------------
Baud300            | 
Baud600            | 
Baud1200            | 
Baud2400            | 
Baud4800            | 
Baud9600            | 
Baud14400            | 
Baud19200            | 
Baud28800            | 
Baud38400            | 
Baud57600            | 
Baud115200            | 

Demo types to pass to [Roomba::baud()](#classRoomba_1a452047d0b88077c1cee8a458ff9cbb6e)

#### `enum `[`Demo`](#classRoomba_1a85c87c27f29d9eb6e01ce96a91cebd4e) 

 Values                         | Descriptions                                
--------------------------------|---------------------------------------------
DemoAbort            | 
DemoCover            | 
DemoCoverAndDock            | 
DemoSpotCover            | 
DemoMouse            | 
DemoDriveFigureEight            | 
DemoWimp            | 
DemoHome            | 
DemoTag            | 
DemoPachelbel            | 
DemoBanjo            | 

Demo types to pass to [Roomba::demo()](#classRoomba_1ae6884b116088ec02f197ae764405e62f)

#### `enum `[`Drive`](#classRoomba_1a2e382956bcc02f04ffd3496f7a44e1c4) 

 Values                         | Descriptions                                
--------------------------------|---------------------------------------------
DriveStraight            | 
DriveInPlaceClockwise            | 
DriveInPlaceCounterClockwise            | 

Special values for radius in [Roomba::drive()](#classRoomba_1ab69511e88b7176c550d0cd55a1547a53)

#### `enum `[`StreamCommand`](#classRoomba_1a430e6f03a756389adcc67762affbc43c) 

 Values                         | Descriptions                                
--------------------------------|---------------------------------------------
StreamCommandPause            | 
StreamCommandResume            | 

Values to pass to [Roomba::streamCommand()](#classRoomba_1aea8864c72aa98210a3106dbafdc99594)

#### `enum `[`EventType`](#classRoomba_1abb4d3274e2698b8f1a670a590adc5c46) 

 Values                         | Descriptions                                
--------------------------------|---------------------------------------------
EventTypeWheelDrop            | 
EventTypeFronWheelDrop            | 
EventTypeLeftWheelDrop            | 
EventTypeRightWheelDrop            | 
EventTypeBump            | 
EventTypeLeftBump            | 
EventTypeRightBump            | 
EventTypeVirtualWall            | 
EventTypeWall            | 
EventTypeCliff            | 
EventTypeLeftCliff            | 
EventTypeFrontLeftCliff            | 
EventTypeFrontRightCliff            | 
EventTypeRightCliff            | 
EventTypeHomeBase            | 
EventTypeAdvanceButton            | 
EventTypePlayButton            | 
EventTypeDigitalInput0            | 
EventTypeDigitalInput1            | 
EventTypeDigitalInput2            | 
EventTypeDigitalInput3            | 
EventTypeModePassive            | 

Values to pass to [Roomba::waitEvent()](#classRoomba_1a9c3bb7040c111c3a3467ecd4b17f0c52)

#### `enum `[`IRCommand`](#classRoomba_1a3d746bbb375be99981ad8ad8cb6c53f6) 

 Values                         | Descriptions                                
--------------------------------|---------------------------------------------
IRCommandLeft            | 
IRCommandForward            | 
IRCommandRight            | 
IRCommandSpot            | 
IRCommandMax            | 
IRCommandSmall            | 
IRCommandMedium            | 
IRCommandLargeClean            | 
IRCommandPause            | 
IRCommandPower            | 
IRCommandArcForwardLeft            | 
IRCommandArcForwardRight            | 
IRCommandDriveStop            | 
IRCommandSendAll            | 
IRCommandSeekDock            | 
IRCommandReserved1            | 
IRCommandRedBuoy            | 
IRCommandGreenBuoy            | 
IRCommandForceField            | 
IRCommandRedGreenBuoy            | 
IRCommandRedBuoyForceField            | 
IRCommandGreenBuoyForceField            | 
IRCommandRedGreenBuoyForceField            | 

Values for sensor packet ID 27

#### `enum `[`ChargeState`](#classRoomba_1ad3b677d855f55252417c538edb50d71f) 

 Values                         | Descriptions                                
--------------------------------|---------------------------------------------
ChargeStateNotCharging            | 
ChargeStateReconditioningCharging            | 
ChargeStateFullChanrging            | 
ChargeStateTrickleCharging            | 
ChargeStateWaiting            | 
ChargeStateFault            | 

Values for sensor packet ID 21

#### `enum `[`Mode`](#classRoomba_1acd756c6947fcbce1df722b864a16b9cd) 

 Values                         | Descriptions                                
--------------------------------|---------------------------------------------
ModeOff            | 
ModePassive            | 
ModeSafe            | 
ModeFull            | 

Values for sensor packet ID 35

#### `enum `[`Sensor`](#classRoomba_1ae1a50282471bf1cf58c637851323054f) 

 Values                         | Descriptions                                
--------------------------------|---------------------------------------------
Sensors7to26            | 
Sensors7to16            | 
Sensors17to20            | 
Sensors21to26            | 
Sensors27to34            | 
Sensors35to42            | 
Sensors7to42            | 
SensorBumpsAndWheelDrops            | 
SensorWall            | 
SensorCliffLeft            | 
SensorCliffFrontLeft            | 
SensorCliffFrontRight            | 
SensorCliffRight            | 
SensorVirtualWall            | 
SensorOvercurrents            | 
SensorIRByte            | 
SensorButtons            | 
SensorDistance            | 
SensorAngle            | 
SensorChargingState            | 
SensorVoltage            | 
SensorCurrent            | 
SensorBatteryTemperature            | 
SensorBatteryCharge            | 
SensorBatteryCapacity            | 
SensorWallSignal            | 
SensoCliffLeftSignal            | 
SensoCliffFrontLeftSignal            | 
SensoCliffFrontRightSignal            | 
SensoCliffRightSignal            | 
SensorUserDigitalInputs            | 
SensorUserAnalogInput            | 
SensorChargingSourcesAvailable            | 
SensorOIMode            | 
SensorSongNumber            | 
SensorSongPlaying            | 
SensorNumberOfStreamPackets            | 
SensorVelocity            | 
SensorRadius            | 
SensorRightVelocity            | 
SensorLeftVelocity            | 

Values for sensor packet IDs to pass to [getSensors()](#classRoomba_1a630c7bb65660c6d0199fec5d64bea465) and [getSensorsList()](#classRoomba_1adacd6f2271766b58c1e5211f8279c69b)

Generated by [Moxygen](https://sourcey.com/moxygen)
