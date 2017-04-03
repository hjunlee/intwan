# intwan
The Intwan is the new interface to Wannier90. Currently, it interfaces QE and VASP to the latest (2.1) wannier90.

# Done
 1. fully in terms of PWs (QE, VASP)
 2. exploit symmetry with SO (QE, VASP)
 3. parallelization (QE, VASP)
 4. compatible with wannier90 2.1 (QE, VASP)
 5. NC, USPP, and PAW with SO (QE)
 
# TODO
 1. paw one-center: necessary?
 2. complete current recipes for symmetry-adapted WFs
 or adopt R. Sakuma's recipe: check wannier90 2.1
 3. automatize construction of WFs:   
   (1). J.I. Mustafa: https://journals.aps.org/prb/abstract/10.1103/PhysRevB.92.165134
 4. complete current recipes for WFs with GW and Hybrid
 5. Wien2k+DMFT
