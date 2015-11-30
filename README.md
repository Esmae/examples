# GMIN, OPTIM and PATHSAMPLE example input
These directories contain example input and output for the **GMIN**, **OPTIM** and **PATHSAMPLE** codes developed in the Wales Group at the University of Cambridge.




## Example systems

### [LJ38](./LJ38) - a 38 atom Lennard-Jones cluster
<img src="LJ38/lj38_gmin.png" width="50%", height="50%">
- Basin-hopping with **GMIN**
- Calculating the mean first encounter time (MFET)
- Connecting minima with a discrete path using **OPTIM**
- Setting up a **PATHSAMPLE** database using an **OPTIM** *path.info* file
- Expanding a **PATHSAMPLE** database in a targeted way

### [tetra-ALA](./tetra_ALA) - an alanine polypeptide (AMBER)
<img src="tetra_ALA/tetra_ALA_igb2_gmin.png" width="50%", height="50%">
- Basin-hopping with **A9GMIN**
- Investigating the effect of removing C-alpha chirality checks 
- Connecting minima with a discrete path using **A9OPTIM**
- Setting up a **PATHSAMPLE** database using an **A9OPTIM** *path.info* file
- Expanding a **PATHSAMPLE** database in a targeted way

### [SER-LYS](./SER_LYS) - a capped dipeptide (AMBER)
<img src="SER_LYS/ser_lys_fe0.6_gmin.png" width="50%", height="50%">

- Basin-hopping with **GMIN**
- Free energy basin-hopping using **A9GMIN8** to investigate the effect of entropy

### [trypzip](./trypzip) - a 12 residue tryptophan zipper (AMBER)
<img src="trypzip/trypzip_endpoints.png" width="50%", height="50%">

**CHALLENGE!**

- Efficiently expand a **PATHSAMPLE** database for a provided initial folding path
- Requires much trial and error! 
