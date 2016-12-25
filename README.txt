----Nong Mun Mun----

Project of Practicum for Computer Engineering (204223)/2016

Developer:
	Natchanan Thongtem / Monpriya Tammavong
	Computer Engineering
	Faculty of Engineering
	Kasetsart Unversity

File Description:
	/firmware - Directory containing
                lib/eeprom.h - containing definition in eeprom.c
                lib/led_board.h - containing definition in led_board.c
                Makefile - make compiling source code and uploading source code to practicum board easiler
                eeprom.c - EEPROM handling extended from avr/eeprom.h
                led_board.c - containging source code to interact with led board for practicum board
                main.c - containing source code that make practicum board can communication with computer and display text on led board
	/java - Direcctory containing 
		BoxMessage.java - show dialog input to get input and convert to 2 dimensional array for sent to board
		McuBoard.java - config USB and contain read, write method to communicate with board
		McuWithPeriBoard.java - extends from McuBoard has medthod sentMessage to sent converted message to board
	lincense.txt - lincense of this project 
	overview.pdf - figure that show all parts of this project
	schematic.pdf - schematic of LED board

This Project is built by C and JAVA with these listing modules
	- C
		- avrlib
                - usbdrv
                - protothreads
	- JAVA
		- Practicum
		- McuBoard
		- JOptionPane

Hardware used in this project:
	- Practicum Board (from 204223 subject)
	- DC Motor
	- Regulator Module
	- Resistor
	- LED
	- Zero pcb
	- Wire (f-m)
	- Wire (f-f)
	- Switch
	- 2 x 4 i/o pin
	- Battery
	- Battery Terminal
