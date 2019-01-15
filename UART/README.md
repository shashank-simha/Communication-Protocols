UART(Universal Asynchronous Receiver Transmitter) Protocol

	* Half Duplex, Serial Communication
	* Two wire (Rx1 to Tx2 & Tx1 to Rx2)
	* Configurable Data format and transfer speed
	* Baud rate
	* Start bit and Stop bit
	* Packet structure :- Start bit + Data frame + Parity bit + Stop bit
						    1 bit     8 or 9 bits     1 bit       1 bit
						    1 to 0                                0 to 1
		total frame size = 1 + 8 + 1 + 1 or 2 = 11 or 12

