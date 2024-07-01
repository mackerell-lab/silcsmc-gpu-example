# silcsmc-gpu

### Description
The GPU version modified on the CPU version of silcs-mc for calculating the conformation and LGFE of a large number of ligands in FragMaps simultaneously.

### Usage
```
silcs_mc.py [-h] [-v] [-s FILE] [--struct_format [SDF|MOL2]] [-o FILE]
                   [--output_format [SDF|PDB]] [-l FILE] [-c x y z] [-d]
                   [--seed arg] [--keepdata] [--long-help]
                   parameter_file
```

### Example
This is an example of silcs-mc-gpu Monte Carlo and genetic algorithm applied to the thrombin system. 
Example source:
https://doi.org/10.1039/D1SC01781K
