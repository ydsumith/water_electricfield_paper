# Lamellar Water Under Electric Fields Using TIP4P-Ew

This repository contains simulation inputs, analysis scripts, processed results, and figures for a molecular dynamics study of lamellar water under applied electric fields using the TIP4P-Ew water model.

---

# Repository Contents

```text
.
├── Effect_of_Efield_NVT.zip
├── TIP4P_Ew_validation_v2.zip
├── lamellar_v6_noslab.zip.001
├── lamellar_v6_noslab.zip.002
├── lamellar_v6_noslab.zip.003
└── README.md
```

---

# Project Description

This repository supports simulations and analysis related to:

- Electric-field effects on lamellar water
- Enthalpy of vaporization
- Dipole orientation distributions
- Density profiles
- Pressure tensor profiles
- Surface tension-related calculations
- TIP4P-Ew water model validation

---

# Archive Details

## Effect of Electric Field — `Effect_of_Efield_NVT.zip`

Contains NVT simulation files and analysis results for electric-field cases.

### Typical Contents

- LAMMPS input scripts
- Simulation logs
- Analysis scripts
- Processed data
- Result figures

---

## TIP4P-Ew Validation — `TIP4P_Ew_validation_v2.zip`

Contains validation simulations and supporting analysis for the TIP4P-Ew water model.

### Typical Contents

- Validation input files
- Benchmark simulation outputs
- Thermodynamic property calculations
- Comparison plots

---

## Lamellar Water Dataset — `lamellar_v6_noslab.zip.001`, `.002`, `.003`

These files are parts of a split archive. Keep all three files in the same folder before extraction.

---

# Extracting the Split Archive

## Linux

```bash
7z x lamellar_v6_noslab.zip.001
```

## Windows

1. Install 7-Zip
2. Place all `.001`, `.002`, and `.003` files in the same folder
3. Right-click `lamellar_v6_noslab.zip.001`
4. Select **7-Zip → Extract Here**

---

# Simulation Overview

| Item | Description |
|---|---|
| Molecular dynamics engine | LAMMPS |
| Water model | TIP4P-Ew |
| Ensemble | NVT / production MD workflows |
| Temperature | 298 K |
| Timestep | 1 fs |
| Main focus | Field-direction-dependent thermodynamic and structural response of lamellar water |

---

# Electric Field Cases

The simulations include electric fields applied parallel and perpendicular to the lamellar water interface.

```text
Ex = 0.00, 0.01, 0.05, 0.10 V/Å
Ez = 0.00, 0.01, 0.05, 0.10, 0.15, 0.20, 0.25 V/Å
```

---

# Typical File Types

| File Type | Description |
|---|---|
| `*.in` | LAMMPS input files |
| `*.data` | Initial structure/data files |
| `*.log` | LAMMPS log files |
| `*.py` | Python analysis scripts |
| `*.m` | MATLAB analysis scripts |
| `*.csv` | Processed data |
| `*.txt` | Text output or tabulated data |
| `*.png`, `*.jpg` | Figures and visualization outputs |

> Large trajectory files may not be included in the repository because of file-size limitations.

---

# Usage Notes

1. Extract the required archive before running scripts
2. Check individual folder paths inside scripts before execution
3. Update file paths if running on a new machine or computing cluster
4. Use the validation archive to verify the TIP4P-Ew setup before reproducing production cases

---

# Citation

If you use this repository, please cite the associated publication once available.

---

# License

This repository is shared for academic and research use. For reuse, redistribution, or collaboration, please contact the author.

# Disclaimer

This repository is provided for academic, educational, and research purposes only.

The simulation inputs, scripts, datasets, and analysis tools contained in this repository are distributed without any warranty, express or implied. While reasonable efforts were made to verify the correctness and reproducibility of the computational workflows and processed results, the authors make no guarantees regarding:

- Completeness of the datasets
- Accuracy of derived quantities
- Suitability for specific applications
- Compatibility across computing environments
- Reproducibility on different hardware or software configurations

Users are responsible for independently validating all simulations, scripts, parameters, and post-processing methods before using them in published research or production environments.

Some large trajectory files and intermediate simulation outputs may be omitted because of repository size limitations. Therefore, certain analyses may require regeneration of data using the provided simulation inputs.

The repository may contain:
- Experimental workflows
- Development-stage scripts
- Archived datasets
- Legacy input configurations

These materials may not reflect the final versions used in associated publications.

By using this repository, users acknowledge that:
- Molecular dynamics simulations are sensitive to implementation details, force-field parameters, boundary conditions, and numerical settings.
- Computational results may vary depending on software versions, compiler settings, hardware architecture, and parallelization methods.
- Proper scientific judgment is required when interpreting or extending the provided results.

The authors are not liable for any direct or indirect damages, data loss, computational expenses, or research outcomes resulting from the use of this repository.

If you use this repository in academic work, please appropriately cite the associated publication(s) and acknowledge the original source.
