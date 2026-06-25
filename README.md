#iCIPT2 results

After extraction, The all_output folder contains iCIPT2 results for core‑excited states and ground state of diatomic molecules, plus ORCA fitted potential energy curves.


## Structure

- **`CO+C`, `CO+O`, `COC`, `COO`, `N2`, `N2+`, `NH+`, `NO+N`, `NO+O`, `NON`, `NOO`**  
  Core‑excited state results for the specified core‑hole (e.g., `CO+C` = C 1s excitation in CO+).  
  Each holds subfolders for different selection thresholds and VEE:
  - `1.0E-5/` : *Cmin* = 1.0×10⁻⁵  
  - `2.5E-5/` : *Cmin* = 2.5×10⁻⁵  
  - `5.0E-5/` : *Cmin* = 5.0×10⁻⁵  
  - `VEE/`   : vertical excitation energies  

  Files inside threshold folders follow the pattern:  
  `CMINx.xE-x_XXX.out`  
  where `XXX` = internuclear distance × 100 (e.g., `080` → 0.80 Å).

- **`ground_state/`**  
  Ground‑state calculations for all molecules.

- **`orca_fit/`**  
  Potential energy curves fitted with ORCA.
