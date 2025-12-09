# Rotational Compressible Boundary Layer

This repository collects reference solutions and datasets for **rotational, compressible boundary-layer flows**.

---

## Repository Layout

At the top level you will find a set of **case directories**:

- `MR00/`
- `MR02/`
- `MR04/`
- `MR06/`
- …

Each case directory is **self-contained** and contain a specific ratational Mach number regime.

> 🔎 **Tip:** open any `MRxx/` directory and inspect the file headers/comments to see the exact column layout and units used in that case.

---

The files are stored in simple, script-friendly formats, so they can be read from:

- **Python** (e.g. with `numpy.loadtxt` / `pandas.read_csv`),
- **MATLAB/Octave** (e.g. `readmatrix`, `dlmread`),
- **Fortran/C++** with standard formatted or unformatted I/O.

---

These boundary-layer datasets have been designed with the **URANOS solver**.

For details on URANOS and its numerics, see the main repository:

- 👉 https://github.com/uranos-gpu/uranos-gpu

If you use these data together with URANOS in scientific work, please also cite the URANOS CPC papers (see “How to Cite” below).

---

## How to Cite

If this repository helps your research, please consider citing:

- **URANOS** (original solver description)  
  F. De Vanna et al., *Computer Physics Communications* (2023), DOI: 10.1016/j.cpc.2023.108717.

- **URANOS-2.0 / extended capabilities**  
  F. De Vanna et al., *Computer Physics Communications* (2024), DOI: 10.1016/j.cpc.2024.109285.

If you build on, extend, or re-distribute these specific rotational boundary-layer datasets, you are encouraged to:

- cite the above URANOS papers, and
- reference this GitHub repository by URL and commit hash.

---

## License

---

## Contact & Contributions

Maintainer: **Francesco De Vanna**  and **Stefano Regazzo**
Affiliation: Department of Industrial Engineering (DII), University of Padova  
Email: `francesco.devanna@unipd.it`

Contributions, bug reports, and suggestions are welcome.  
Feel free to open an issue or a pull request if you:

- spot mistakes in the profiles or documentation,
- have scripts for reading or visualizing the datasets that could help other users.

---
