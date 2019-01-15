I2C(Inter-Integrated-Circuit) Protocol

	* Half Duplex, Serial Communication
	* Synchrounous
	* Two wire (Data & Clock)
	* Multi master and Multi slave
	* MSB first
	* Packet structure :- Start + Device Address + R/W + Ack + Data + Ack + Data + Ack + Stop
						  1 bit    7 or 10 bits   1 bit 1 bit 8 bits 1 bit 8 bits 1 bit  1 bit
								  
	* Start condition: SDA(data line) - High to Low
					   SCL(clock line) - High
	* Stop condition: SDA(data line) - Low to High
					   SCL(clock line) - High
	* R/W : 1 - Read
		    0 - Write 
	* Number of slaves = 2^7=128 or 2^10=1024

