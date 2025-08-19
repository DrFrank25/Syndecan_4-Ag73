Molecular Dynamics Analysis Plot This repository contains Python scripts designed to ploting and visualization of Molecular Dynamics (MD) simulation data, with a focus on trajectory descriptors frequently used in structural biology and computational chemistry.

The scripts support input files in GROMACS .xvg format and produce high-quality publication-ready plots.

Features

Root Mean Square Deviation (RMSD) Reads RMSD .xvg files from GROMACS. Applies Savitzky–Golay smoothing or running average filters to reduce noise. Plots both raw and smoothed curves for multiple independent runs (replicates). Calculates: Per-run mean and standard deviation. Global average and standard deviation across all runs. Saves figures in high resolution (1200 dpi) for publication.
Root Mean Square Fluctuation (RMSF) Reads RMSF .xvg data. Plots residue-wise fluctuations. Highlights flexible vs. stable regions of the protein.
Radius of Gyration (Rg) Processes .xvg files from gmx gyrate. Displays the time evolution of the protein’s compactness. Calculates mean and standard deviation across replicates.
Solvent Accessible Surface Area (SASA) Reads .xvg data from gmx sasa. Plots SASA curves with optional smoothing. Supports averaging across multiple simulation runs. Output Plots: High-quality, publication-ready PNG figures. Statistics: Mean and standard deviation printed for each run and globally across all runs. Legends: Customizable, with run labels (e.g., Run 1, Run 2, Run 3). Export: Figures can be downloaded directly in Google Colab or saved locally. Requirements Python 3.8+ NumPy Pandas Matplotlib SciPy Google Colab (for interactive use) Usage Upload .xvg files (RMSD, RMSF, Rg, SASA) into the Colab notebook. Run the corresponding script. Figures and statistics will be generated automatically. Download the figures.
About
Molecular dynamics plot

Resources
 Readme
License
 CC0-1.0 license
Security policy
 Security policy
 Activity
Stars
 0 stars
Watchers
 0 watching
Forks
 0 forks
Releases
No releases published
Create a new release
Packages
No packages published
Publish your first package
Footer
