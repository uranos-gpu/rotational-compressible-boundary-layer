# Rotational Compressible Boundary Layer

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17870172.svg)](https://doi.org/10.5281/zenodo.17870172)

This repository collects **reference solutions and datasets** for **rotational, compressible boundary-layer flows**, intended for inflow generation, validation, and theoretical analysis.

---

## Repository Layout

At the top level you will find the **case directories**:

- `MR00/`
- `MR02/`
- `MR04/`
- `MR06/`
- …

Each directory contains a **self-contained laminar compressible boundary-layer solution** for a specific **rotational Mach number** regime.

> 🔎 **Tip:** open any `MRxx/` directory and inspect the headers in the data files to see the exact column layout and units.

---

## Usage

The datasets are stored in simple, script-friendly formats and can be read from:

- **Python** (`numpy.loadtxt`, `pandas.read_csv`)
- **MATLAB/Octave** (`readmatrix`, `dlmread`)
- **Fortran/C++** using formatted/unformatted I/O

They are suitable for:

- inflow conditions in high-fidelity DNS/LES/WMLES,
- validation of compressible boundary-layer models,
- stability and transition studies,
- testing wall-transformation and compressibility models.

---

## Relation to URANOS

These boundary-layer datasets were generated for use with the **URANOS solver** for compressible wall-bounded flows.

Main solver repository:

👉 https://github.com/uranos-gpu/uranos-gpu

If you use these datasets with URANOS, please consider citing the URANOS CPC papers (see below).

---

## How to Cite

If this repository helps your research, please cite:

**Dataset DOI**

- De Vanna & Regazzo (2025). *Rotational Compressible Boundary Layer Dataset.*  
  DOI: [10.5281/zenodo.17870172](https://doi.org/10.5281/zenodo.17870172)

**URANOS solver**

- F. De Vanna et al., *Computer Physics Communications* (2023),  
  DOI: 10.1016/j.cpc.2023.108717  
- F. De Vanna et al., *Computer Physics Communications* (2024),  
  DOI: 10.1016/j.cpc.2024.109285

If you extend or redistribute the datasets, please reference this repository and the appropriate DOI.

---

## License

This project is released under the **MIT License**, a permissive open-source license allowing reuse, modification, and redistribution with attribution.

See the [`LICENSE`](./LICENSE) file for the full text.

---

## Contact & Contributions

Maintainers: **Francesco De Vanna**, **Stefano Regazzo**  
Affiliation: Department of Industrial Engineering (DII), University of Padova  
Email: `francesco.devanna@unipd.it`

Contributions, issues, and suggestions are welcome.  
Feel free to open an issue or pull request if you:

- identify inconsistencies in the datasets,
- want to add new Mach/Re/temperature regimes,
- have scripts or visualizations useful for other users.

---
