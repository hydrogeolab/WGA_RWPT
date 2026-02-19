# WGA_RWPT


WGA_RWPT ("Warm-start Genetic algorithm coupled with Random-Walk Particle Tracking" ) is a MATLAB/OCTAVE and Python code. It can be used to optimize hydraulic barriers (HBs) used for solute plume containment in polluted aquifers. WGA_RWPY is framed on a simulation–optimization framework that coupled a warm-start genetic algorithm (GA) with parallel RWPT to identify minimal pumping rates for HB containment in a computationally efficient manner. 

For more information and for using it, please refer to and cite 
D. Pedretti, "_Hydraulic barrier optimization under stochastic solute transport: effects of dispersion, particle discretization, and algorithmic initialization_" (under review on Water Resources Research).

Notes for the user: 
1) Currently, only the MATLAB code is fully tested (using MATLAB v.2024b)
2) To use with OCTAVE, the user requires minimum adjustments to the .m files
3) Executables for the flow (MODFLOW-2005) and the random walk particle tracking (PAR2) codes are not included in the distribution. MODFLOW-2005 can be found at https://www.usgs.gov/software/modflow-2005-usgs-three-dimensional-finite-difference-ground-water-model (accessed on 12 February 2026), and PAR2 can be found at https://github.com/GerryR/par2 (accessed on 12 February 2026).
4) The Python version is "beta" and currently enables only cold-start initialization.
5) The example provided is limited to 10 realizations, for a matter of space availability.

WGA_RWPT is free and open-source software under the GNU GPLv3 license. https://www.gnu.org/licenses/gpl-3.0.html. No warranty, expressed or implied, is made by the authors or corresponding affiliations as to the correct functionality of the software and related material, nor shall the fact of release constitute any such warranty.
