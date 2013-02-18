PLEASE NOTE:

I have stopped updating this branch of my code, please go to the NetSPI github to get the latest version:
https://github.com/NetSPI/PS_MultiCrack

READ ME

-You need to specify your rcrack, john, perl, and rainbow table directories in the script-

Usage: PS_MultiCrack.ps1 INPUT_FILE OUTPUT_FILE

Hashes in the input file need to be in this format:
	Domain\User:::LMHASH:NTLMHASH:1122334455667788
	
The output file writes to the directory that you run this script from.