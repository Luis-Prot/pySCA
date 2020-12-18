# pySCA

Version 03.2015 

Original Author: Reynolds
Copyright (C) 2015 Olivier Rivoire, Rama Ranganathan, Kimberly

This repository is a Fork of [Reynoldsk](https://github.com/reynoldsk), if you wish to view the original repository click [here](https://github.com/reynoldsk/pySCA).

**This program is free software distributed under the BSD 3-clause license, please see the file LICENSE for details.**

The current version of the Statistical Coupling Analysis (SCA) analysis is implemented in python. This directory contains the necessary code for running the SCA calculations, as well examples/tutorials for the dihydrofolate reductase (DHFR) enzyme family, the S1A serine proteases, the small G-protein family and the Beta-lactamase enzyme
family. The tutorials are distributed as iPython notebooks.

For installation instructions, I recomend a virtual enviroment in Python3

## Make a Virtualenv


# Content and Scripts
- `Inputs/`: Directory containing input files (including those needed for the tutorials)
- `Outputs/`: Directory for output files (empty at install)
- `html_docs/`: Directory containing html documentation
- `annotate_MSA.py`: Python script that annotates alignments with phylogenetic/taxonomic information   
- `scaProcessMSA.py`: Python script that conducts some initial processing of the sequence alignment
- `scaCore.py`: Python script that runs the core SCA calculations
- `scaSectorID.py`:  Python script that defines sectors given the results of the calculations in scaCore
- `scaTools.py`: The SCA toolbox - contains all functions needed for the SCA calculations
- `SCA_DHFR.ipynb`: Python notebook example for DHFR
- `SCA_G.ipynb`: Python notebook example for the small G proteins
- `SCA_betalactamase.ipynb`: Python notebook example for the beta-lactamases
- `SCA_S1A.ipynb`: Python notebook example for the S1A serine protease

