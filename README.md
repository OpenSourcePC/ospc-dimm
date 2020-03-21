# ospc-dimm
Open Source DIMM modules.

For a contribution guide, see CONTRIBUTING.md

## JEDEC Standard Breaks

 * PCB layer count: For ease of assembly, we are using 4-layer PCBs. The outer layers are power, the inner layers are data.

## Folder format

`ospc-ddr[ddr version]-[dimmtype]-[number of ranks]r-x[data bus width of modules, comma seperated if mixed]-[S if SPD only, T if SPD + temp sensor]`

## Subprojects

`✔️: done ❓: done but needs verification, ❌: not done`

Projects marked for verification may not be functioning properly.

 * `ospc-ddr4-udimm-1r-x16-t` : UDIMM, DDR4, 1 rank, x16 (96ball), SPD+Temp (Schematic ❓, PCB ❌)