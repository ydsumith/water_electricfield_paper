# Lamellar Water Under Electric Fields Using TIP4P-Ew

This repository contains simulation inputs, scripts, processed results, and figures for a molecular dynamics study of lamellar water under applied electric fields using the TIP4P-Ew water model.

## Repository Contents

```text
.
├── Effect_of_Efield_NVT.zip
├── TIP4P_Ew_validation_v2.zip
├── lamellar_v6_noslab.zip.001
├── lamellar_v6_noslab.zip.002
├── lamellar_v6_noslab.zip.003
└── README.md

Description

The files in this repository support simulations and analysis related to:

Electric-field effects on lamellar water
Enthalpy of vaporization
Dipole orientation distributions
Density profiles
Pressure tensor profiles
Surface tension-related calculations
TIP4P-Ew water model validation
Archive Details
Effect_of_Efield_NVT.zip

Contains NVT simulation files and analysis results for electric-field cases.

Typical contents may include:

LAMMPS input scripts
Simulation logs
Analysis scripts
Processed data
Result figures
TIP4P_Ew_validation_v2.zip

Contains validation simulations and supporting analysis for the TIP4P-Ew water model.

Typical contents may include:

Validation input files
Benchmark simulation outputs
Thermodynamic property calculations
Comparison plots
lamellar_v6_noslab.zip.001, .002, .003

These are parts of a split archive. Keep all three files in the same folder before extraction.

To extract on Linux:

7z x lamellar_v6_noslab.zip.001

To extract on Windows:

Install 7-Zip.
Place all .001, .002, and .003 files in the same folder.
Right-click lamellar_v6_noslab.zip.001.
Select 7-Zip → Extract Here.
Simulation Overview
Molecular dynamics engine: LAMMPS
Water model: TIP4P-Ew
Ensemble: NVT / production MD workflows
Temperature: 298 K
Timestep: 1 fs
Main focus: field-direction-dependent thermodynamic and structural response of lamellar water
Electric Field Cases

The simulations include electric fields applied parallel and perpendicular to the lamellar water interface, including cases such as:

Ex = 0.00, 0.01, 0.05, 0.10 V/Å
Ez = 0.00, 0.01, 0.05, 0.10, 0.15, 0.20, 0.25 V/Å
Typical File Types
*.in          LAMMPS input files
*.data        Initial structure/data files
*.log         LAMMPS log files
*.py          Python analysis scripts
*.m           MATLAB analysis scripts
*.csv         Processed data
*.txt         Text output or tabulated data
*.png, *.jpg  Figures and visualization outputs

Large trajectory files may not be included in the repository because of file-size limitations.

Usage Notes
Extract the required archive before running scripts.
Check individual folder paths inside scripts before execution.
Update file paths if running on a new machine or cluster.
Use the validation archive to verify the TIP4P-Ew setup before reproducing production cases.

Citation

If you use this repository, please cite the associated publication once available.

Contact

Sumith Yesudasan
Assistant Professor
Department of Mechanical and Industrial Engineering
University of New Haven

License

This repository is shared for academic and research use. For reuse, redistribution, or collaboration, please contact the author.
