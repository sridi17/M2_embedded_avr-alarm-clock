# REQUIREMENTS #


# INTRODUCTION #
- In this project we are going to design a simple Alarm clock using ATMEGA32 timers.
 ATmega32A microcontroller has a 16 bit timer,
 and we will be using that timer to count the seconds and develop a digital clock.
- All the digital clocks have a crystal inside of them which is the heart of clock. 
- This crystal not only present in clock but present in all computing real time systems. 
- This crystal generates clock pulses, which is needed for timing calculations. 
- Although there are some other ways to get clock pulses but for accuracy and higher frequency most prefer crystal based clock.
-  We are going to connect a crystal to ATMEGA32 for getting accurate clock.

# SWOT ANALYSIS #

# STRENGTH #
- Still runs on 5 V, so legacy 5 V stuff interfaces cleaner
- Even though it's 5 V capable, newer parts can run to 1.8 V. This wide range is very rare.
- Nice instruction set, very good instruction throughput compared to other processors (HCS08, PIC12/16/18).
- High quality GCC port (no proprietary crappy compilers!)
- "PA" variants have good sleep mode capabilities, in micro-amperes.

# weakness #
- Still 8-bit. An ARM is a 16/32-bit workhorse, and will push a good amount more data around, at much higher clock speeds, than any 8-bit.
- Cost Can be expensive compared to HCS08 or other bargain 8-bit processors.
- GCC toolchain has quirks, like the split memory model and limited 16-bit pointers.
- Atmel is not the best supplier on the planet (at least they're not Maxim...)

# opportunity #
The high-performance, low-power Microchip 8-bit AVR® RISC-based microcontroller combines 32 KB ISP flash memory with read-while-write capabilities, 1 KB EEPROM, 2 KB SRAM, 54/69 general purpose I/O lines, 32 general purpose working registers, a JTAG interface for boundary-scan and on-chip debugging/programming, three flexible timer/counters with compare modes, internal and external interrupts, serial programmable USART, a universal serial interface (USI) with start condition detector, an 8-channel 10-bit A/D converter, programmable watchdog timer with internal oscillator, SPI serial port, and five software selectable power saving modes. The device operates between 1.8-5.5 volts.
By executing powerful instructions in a single clock cycle, the device achieves throughputs approaching one MIPS per MHz, balancing power consumption and processing speed.

