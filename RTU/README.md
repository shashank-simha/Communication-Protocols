
Modbus RTU(Remote Terminal Unit) Protocol - RS485

	* Long distance (upto 1200m)
	* Serial slaves(multiple slave)
	* Single master with multiple Rx and Tx
	* Start and Stop : 28 bits or 3.5 chars 
	* CRC error checking
	* Packet structure :- Start + Address + Function code +  Data  +  CRC +  Stop
						 28 bits   8 bits      8 bits      N*8 bits 16 bits 28 bits

