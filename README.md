# LEDController
## I cannot upload the code due to class restrictions as this was done as a final project 
A LED light control app is designed using a microcontroller, UART, and Timer peripherals. It utilizes push buttons (PBs) to toggle between ON/OFF modes and blinking modes for the LED connected to pin 12, while capturing and plotting intensity levels and PWM voltage output vs. time using Python for analysis and visualization. 

ADC ->This code initializes and
performs analog-to-digital conversion
(ADC) on pin 8/RA3/AN5 using the
ADC module, returning a 10-bit ADC
value in unsigned integer form.

ChangeClk -> This code snippet
defines a function NewClk that
changes the system clock frequency
based on the input parameter clkval

UART -> This code initializes and
manages UART2 communication on
PIC facilitating transmission of
characters, hexadecimal and decimal
numbers, as well as strings over
UART to an external device.

IOs -> This code handles button
presses (PB1 and PB2) to control
system states using interrupts,
enabling functionalities like clock
switching, UART communication,
ADC sampling, and LED blinking.

TimeDelay -> This code implements
time delay functions in milliseconds
and microseconds using Timer 1 and
Timer 2 interrupts, configuring the
timers and interrupts accordingly
for precise timing.
