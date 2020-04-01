GDB:
	run
		Runs until the next breakpoint

	break *<memory address> (ex: break *0x4005c8)
		Puts a breakpoint at the given memory address
		
	i r
		Inspects registers

	x/<n>xb <memory address> (ex: x/4xb $rbp)
		Prints the specified number of bytes at a given location
		