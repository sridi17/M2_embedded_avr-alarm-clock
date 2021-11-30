# REQUIREMENTS #


# INTRODUCTION #
-Digital wall clocks are common items seen in almost every household, office, and industry.
- It is a common but essential household item that allows us to get our bearings and gives us a sense of the day we are spending. 
- Buying a new wall clock will generally cost you a bit more money than you would initially expect since it is the basic habit of shopkeepers to dupe their customers.
-  But luckily there is a simple way of making a digital wall clock. 


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

# 4W & 1H #
# WHY #
- All the digital  wall clocks have a crystal inside of them which is the heart of clock.
-  It is a common but essential household item that allows us to get our bearings and gives us a sense of the day we are spending. 
- Buying a new wall clock will generally cost you a bit more money than you would initially expect since it is the basic habit of shopkeepers to dupe their customers.
-  But luckily there is a simple way of making a digital wall clock. 



# WHAT #
- These DIY Digital wall clock are usually used in places such as offices, homes, schools
- Also used in appliances such as ovens, food timers, washing machines, etc.


# WHEN #
- For accurate timing, we have connected a 11.0592MHz crystal for clock.
- Now for disabling the internal clock of ATMEGA we have to change its LOW FUSE BITS. 
- Remember we are not touching the high fuse bits so the JTAG communication would be still enabled.

# HOW #
- through lcd display we can see the digital time.

# LOW LEVEL REQUIREMENT
# HADWARE COMPONENT
MCU IC	Microchip ATMega328p	1
2)	Arduino Uno Board	Rev3, 8KB	1
3)	Crystal Oscillator	16MHz	1
4)	IC Base	28 – pin	1
5)	7 – segment display	common anode	4
6)	Capacitors	22pF	2
7)	Resistors	220 Ohm, 1K	28
8)	LED	5mm, 3.5V	1
9)	Header Pins	Female/male	2
10)	Soldering Iron	45W – 65W	1
11)	Soldering Wire with Flux	–	1
12)	Pushbutton	–	1
13)	Toggle switch	–	2
14)	Veroboard	–	1
15)	DC Battery with Clip	3.7V	1
16)	Jumper Wires	
# HIGH LEVEL REQUIREMENT
AVR compiler,simule ide


