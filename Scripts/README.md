'A1-LCD_ion_calculations.ipynb' jupyter notebook contains two seprate functions:
1: Calculate ion counts for a specifc amino acid type
2: Calculate the number of ions that bridge 'x' number of chains

For each script, the input files come from the output of CPPTRAJ mask calculations for ions/residues within a given cutoff (in .dat format) for an individual chain that has been centered in a multi-chain simulation.

These functions calculate unique ion-protein interactions. 

For detemining total ions within a given cutoff, the 2nd calculation can be used (which gives unique ion totals for each number of bridged chains including 1-chain interactions) by summing these totals for a given ion type/cutoff distance. 

Details of variables that need to be adjusted are documented in comments throughout the notebook.
 
These were written with data from 4 replicate simulations, on 2500 frames each, but can be adjusted as needed.





