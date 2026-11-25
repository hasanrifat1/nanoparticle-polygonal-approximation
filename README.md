# Nanoparticle polygonal approximation

Supporting data and MATLAB code for regularized polygonal approximation of nanoparticle boundaries from transmission electron microscopy (TEM) images.

## Method
The workflow uses roundness-based classification followed by:
1. AIC-based greedy backward vertex pruning.
2. Bootstrap-guided simpler polygon selection.
3. Uncertainty-guided vertex merging.

The resulting polygons characterize apparent two-dimensional projected geometry, not independently verified crystallographic facets.

## Planned repository contents
- `code/`: MATLAB implementation and analysis scripts.
- `data/simulation/`: simulated boundaries, design parameters and recovery results.
- `data/experimental/`: approved processed particle boundaries and geometric measurements for Pd nanoparticles on crystalline and amorphous supports.
- `results/`: numerical data underlying manuscript figures and tables.
- `documentation/`: data dictionary and reproduction instructions.

## Status
Repository under preparation. The folders currently contain documentation placeholders only. MATLAB files and datasets have not yet been deposited. Reproduction instructions and software dependencies will be finalized after the scripts are uploaded and tested.

## Data permissions
Original TEM images and derived experimental data must not be released until applicable permissions are confirmed. Licensing and citation details will be finalized before public release.
