# GloFAS Training: ICAR 2026 Workshop

Hands-on training materials for the **5th International Conference on African Rivers (ICAR 2026)** on hydrological forecasting with the **Global Flood Awareness System (GloFAS)**.

This Jupyter Book teaches you how to access, analyze, and evaluate global flood forecasts using Python and data from ECMWF's Copernicus Emergency Management Service (CEMS).

## Quick Start

### 1. Set up your environment

```bash
conda env create -f environment.yml
conda activate icar-2026-glofas
```

### 2. Build and view the book locally

```bash
jupyter book build .
jupyter book open _build/html/index.html
```

### 3. Or run notebooks in the browser

Click **"Launch" → "Binder"** on the published book to run code online without installation.

## 📚 Workshop Modules

| # | Topic | Learn to |
|---|-------|----------|
| 1 | Data Access | Download GloFAS data from CEMS Early Warning Data Store |
| 2 | Simulation Evaluation | Evaluate GloFAS simulation skill and accuracy |
| 3 | Historical Analysis | Analyze river discharge and climatology patterns |
| 4 | Deterministic Forecasts | Work with GloFAS point forecasts |
| 5 | Ensemble Forecasts | Interpret probabilistic ensemble predictions |
| 6 | Seasonal Forecasts | Analyze long-range seasonal outlooks |

## 📋 Requirements

- Python 3.12+
- Conda or Mamba
- A free [Copernicus CDS account](https://cds.climate.copernicus.eu) (needed for data downloads)

## 🛠️ Key Libraries

- **cdsapi** — Access Copernicus CDS climate data
- **xarray** — Multi-dimensional data manipulation
- **netCDF4** — Climate data I/O
- **cartopy** — Geospatial visualization
- **matplotlib** — Plotting and visualization

## 📖 Documentation

Full interactive book: https://simow-az.github.io/ICAR-2026-GloFAS-Training/

The notebooks are self-contained with explanations and code examples throughout.

## 📄 License

Apache License 2.0 — See [LICENSE](LICENSE) file.

## 👨‍🏫 Credits

Developed by **ECMWF** as part of the ICAR 2026 training programme.

---

**New to GloFAS?** Start with Workshop 1 to learn data access, then progress sequentially through the modules.
