SPI(Serial Peripheral Interface) Protocol

	* Full Duplex, Serial Communication
	* Synchrounous
	* Four wire (Clock, MISO, MOSI, Slave Select)
	* Single master and Multi slave
	* Uses shift registers
	* MSB first, No acknowledge signals
	* Clock Polarity : Idle state = 0 -> Polarity = 0
					   Idle state = 1 -> Polarity = 1
	* Clock Polarity(CPOL)		R/W			Clock Phase(CPHA)		Mode
			0				Falling edge		0				   Mode 0
			0				Rising edge			1				   Mode 1
			1				Rising edge			0				   Mode 2
			1				Falling edge		1				   Mode 3

