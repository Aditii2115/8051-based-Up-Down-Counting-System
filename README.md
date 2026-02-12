# Up Down Counter using 8051 Microcontroller
Project Overview

This project implements an Up-Down Counter using the 8051 microcontroller (AT89S51). The counter increments or decrements based on push-button input and displays the count on two 7-segment displays. 
The project demonstrates 8051 programming, port interfacing, digital counting logic, and display control.

Features

- Up counting and down counting
- Two 7-segment display output
- Push-button control
- Count range: 00 to 99
- Wrap-around counting logic

Hardware Components

- AT89S51 microcontroller
- Two 7-segment displays
- Push buttons (UP and DOWN)
- Crystal oscillator
- Resistors
- Breadboard and wires

Working Principle

- The AT89S51 microcontroller controls the entire circuit.
- Push button at P1.0 → Increment counter
- Push button at P1.1 → Decrement counter
- Port 2 drives the tens display
- Port 3 drives the units display 

A crystal oscillator provides the clock signal required for microcontroller operation. 

When the count exceeds 99, it resets to 00.

When the count goes below 00, it resets to 99. 

Algorithm

- Initialize ports and counter.
- Split counter into tens and ones digits.
- Display values on 7-segment displays.
- Check UP button press → increment counter.
- Check DOWN button press → decrement counter.
- Repeat loop.

Applications

- Digital clocks
- Scoreboards
- Event counters
- Elevator floor indicators
- Production automation systems  
