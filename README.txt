----Nong Mun Mun----

Project of Practicum for Computer Engineering (204223)/2016

Developer:
	Natchanan Thongtem / Monpriya Tammavong
	Computer Engineering
	Faculty of Engineering
	Kasetsart Unversity

File Description:
	/firmware - Directory containing
		eeprom.c - 
		led_board.c - 
		main.c - 
	/java - Direcctory containing 
		BoxMessage.java - show dialog input to get input and convert to 2 dimensional array for sent to board
		McuBoard.java - config USB and contain read, write method to communicate with board
		McuWithPeriBoard.java - extends from McuBoard has medthod sentMessage to sent converted message to board
	lincense.txt - lincense of this project 
	overview.pdf - figure that show all parts of this project
	schematic.pdf - schematic of LED board

This Project is built by C and JAVA with these listing modules
	- C
		-
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