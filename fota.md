For more information visit: https://confluence.auto.continental.cloud/display/SCCSGP/Traveo+II+Body+High+4M+%28TVIIBH4M%29+Documentation

## Current Setup
- Currently the pi is acting as the gateway to connect to the backend.
- Still figuring out how I should run some updates
- To access backend, TVII will use the key in the work flash to request for and update? (In Progress)

```Current size 1675 bytes with an offset of 0```

Backend <-> Pi <-> TVII

## To Access TVII
- I've already simplified everything. All you have to do is connect to TVII over telnet


## Useful Commands
- flash banks
- flash write_bank \<number\> \<filepath\> \<offset\>
- flash read_bank \<number\> \<outfile_path\> \<offset\> \<size\>
