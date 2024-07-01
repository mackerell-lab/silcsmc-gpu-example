# silcsmc-gpu

### Description
The GPU version of SILCS-MC is of utility for calculating the conformation and LGFE of a large number of ligands in the field of the SILCS FragMaps simultaneously. The GPU version shows ~200-fold speed increase over the CPU version.

### Usage
```
silcs_mc.py [-h] [-v] [-s FILE] [--struct_format [SDF|MOL2]] [-o FILE]
                   [--output_format [SDF|PDB]] [-l FILE] [-c x y z] [-d]
                   [--seed arg] [--keepdata] [--long-help]
                   parameter_file
```

### Example
This is an example of silcs-mc-gpu Monte Carlo and genetic algorithm applied to the protein thrombin. 
Thrombin data may be obtained from https://doi.org/10.1039/D1SC01781K
