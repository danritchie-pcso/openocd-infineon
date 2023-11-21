For more information visit: https://confluence.auto.continental.cloud/display/SCCSGP/Traveo+II+Body+High+4M+%28TVIIBH4M%29+Documentation

## Current Setup
- Currently the pi is acting as the gateway to connect to the backend (Still working on some internet routing issues).
- Still figuring out how I should run some updates and if this is really the best way to do this.
- To access the backend, I have created a service for the TVII will read the key in the work flash which the gateway will utilise to request for and update? (In Progress)

```Currently the key is stored at 0x1400c000 with size of 1675 bytes```

Backend <-> Pi <-> TVII

## To Access TVII
- I've already simplified everything with some scripts. All you have to do is connect to TVII over telnet!


## Useful Commands
- flash banks
- flash write_bank \<number\> \<filepath\> \<offset\>
- flash read_bank \<number\> \<outfile_path\> \<offset\> \<size\>

*Connect to the pi on our internal network at 192.168.1.123*
