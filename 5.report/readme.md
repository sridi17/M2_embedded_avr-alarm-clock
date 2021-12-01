# REPORT #


# REQUIREMENTS #


# INTRODUCTION #
- This project deals with the designing of a seven-segment display(SSD) I2C driver using ATmega328.
- in most applications, however, using a single-digit seven-segment display (SSD), may not be sufficient to display the entire information, hence multiple SSD units are         connected in parallel.
- Therefore, when using a microcontroller to operate a seven-segment LED display, 8 pins are required to control individual LEDs in the display, which can be brought down to   4 using a decoder.

# SWOT ANALYSIS #

# STRENGTH #
-  ATmega328P is a high performance yet low power consumption 8-bit AVR microcontroller.
-  that’s able to achieve the most single clock cycle execution of 131 powerful instructions thanks to its advanced RISC architecture.
-  It can commonly be found as a processor in Arduino boards such as Arduino Fio and Arduino Uno.

# weakness #
- Processors are simpler to use, with the usage of 8bit and 16bit instead of 32/64bit which are more complex.
- Readily usable without additional computing components with 32k bytes of onboard self-programmable flash program memory as well as 23 programmable I/O lines Code Efficient.
-  all 31 registers are directly connected to the arithmetic logic unit (ALU), making it 10 times faster than conventional CISC microcontrollers
- Optimized for AVR enhanced RISC instruction set

# opportunity #
ATmega328P is a low-power CMOS 8-bit microcontroller based on the AVR enhanced RISC architecture. The ATmega328P achieves throughputs approaching 1MIPS per MHz By executing powerful instructions in a single clock cycle. This allows system designers to optimize power consumption versus processing speed very easily. ATMega328p is one of the famous MCUs of Atmel because of its use in the Arduino UNO board. ATmega328P is designed with low current consumption features. The chip contains 32 kilobytes of internal flash memory, 1KB of EEPROM, and 2KB of SRAM.
# THREAT # 
- High up-front costs
- Performance standardization has not yet been streamlined.


# TEST PLAN AND OUTPUT #


# Table No 1: High level test plan

|Test ID |	Description	Exp I/P	Exp O/p |
|------- |  --------------------------- |
| H_01 | Check if program is running or not.|
| H_02 | Check if circuit connection is correct or not |
| H_03 | check if running or not |
# Table No 2: Low level test plan
|Test ID |	Description	Exp I/P	Exp O/p |
|------- | ---------------------------- |
|L_01 |	requirements showld be appropriate |
|L_02 |	required software showld be uploaded.|
|L_03	| should set a correct directory path |


![image](https://user-images.githubusercontent.com/94300992/144233365-e31d3580-19d6-4609-a732-9f8d5f9b5827.png)







# 4W & 1H #
# WHY #
- In most applications, however, using a single-digit seven-segment display (SSD),
-  may not be sufficient to display the entire information, hence multiple SSD units are connected in parallel.
-   In order to display different characters, symbols or numbers, 
-   the data being displayed on each SSD has to be different. 


# WHAT #
- In the case of interfacing a microcontroller with an SSD display,
- using another microcontroller as a driver which acts as a peripheral to the main microcontroller can be very helpful.

# WHEN #
-  When connected with the appropriate I2C master device which identifies its slave address, 
-  the data sent from the master (in this case light intensity) is printed on to the display.



# HOW #
- through seven sigment display we can see the digital time.

# LOW LEVEL REQUIREMENT
# HADWARE COMPONENT
- Hardware components
- ATmega328	
- 7 Segment LED Display
- General Purpose Transistor NPN	
- Through Hole Resistor, 680 ohm	
- 16 MHz Crystal	 
- Capacitor 22 pF	
- Capacitor 10 µF		
- Capacitor 100 nF	
- Resistor 10k ohm	
- SparkFun USB to Serial Breakout - FT232RL	
- SparkFun USB to Serial Breakout - FT232RL

# HIGH LEVEL REQUIREMENT
AVR compiler,simule ide



# OUTPUT #
![SimulIDE-0 4 15-SR9  -  voltimeter_mega328 simu 01-12-2021 14_32_06 (2)](https://user-images.githubusercontent.com/94300992/144230050-0c3c7e54-01a6-439d-a8e3-7eaa28085da4.png)












