# TM Defects in Silicon Carbide

Research projects focused on transition metal defects in silicon carbide.

## Contents

### 0 - Basis Sets Information
This folder contains:
- **ANO Basis sets.txt**: Details about ANO basis sets used in calculations.
- **Basis sets.txt**: General information about the basis sets.
- **General Info.txt**: Overview of the basis sets and their applications.
- **Input chunks.txt**: Input data for simulations.

### 0 - Madelung (Wrong Try)
This folder contains:
- Various coordinate files (Cartesian and fractional) for Cr atoms.
- Subfolders like `Cartesian_coords_armstrong` and `example_unit_cell` for specific configurations.
- **fractional_coords.ipynb**: Notebook analyzing fractional coordinates.
- **non_rel_basis_9_active_Madelung**: Data related to Madelung calculations.

### 1. Point Charge Model (Preliminary Calculations)
This folder contains:
- **change of c plots.ipynb**: Notebook analyzing changes in parameter `c`.
- Subfolders `Input files` and `Output files` for simulation data.
- **results_no_so_C3v.ipynb**: Results without spin-orbit coupling.

### 2. Point Charge Model
This folder contains:
- Subfolders `non_rel_basis_5_active` and `non_rel_basis_9_active` for different basis sets.

### 3. Real Atom Calculations with OpenMolcas
This folder contains:
- **coord_input_shifting.ipynb**: Notebook for shifting coordinate inputs.
- **data_from_sims_17_atoms**: Data from simulations involving 17 atoms.
- **elec_struc_17_real_atoms.ipynb**: Electronic structure analysis for 17 real atoms.

### 4. AMS Calculations for SiC-4H
This folder contains:
- Subfolders for different transition metals (e.g., Cr, Mo, Nb, etc.).
- **0 - PDOS results**: Projected Density of States results.
- **0 - Preliminary calculations**: Initial AMS calculations.
- **0 - Spin Population**: Spin population analysis.
- **README.txt**: Additional details about the AMS calculations.

## Recommendations
- **Keep**: Folders `1. Point Charge Model`, `3. Real Atom Calculations with OpenMolcas`, and `4. AMS Calculations for SiC-4H` as they contain critical data and results.
- **Consider Removing**: `0 - Madelung (Wrong Try)` as it appears to be an incorrect attempt, and `0 - Basis Sets Information` if the basis set details are no longer relevant.