
# 🔬 Density Estimation Module — Eridanus Supervoid

This folder contains the essential scripts required to reconstruct the radial density profile \(\rho(r)\) of the Eridanus Supervoid using observational data and adaptive smoothing techniques.

---

## 📁 Contents

- `Eridanus_sdss.py`  
  Script to download and filter galaxy data from public catalogs (SDSS, Gaia, unWISE) in the region of the Eridanus Supervoid.

- `Density_Estimation_Wavelet_SPH.py`  
  Applies a hybrid Wavelet-SPH algorithm to estimate local densities and build a radial profile.

---

## ⚙️ How to Use

1. **Run the data query script**:

```bash
python Eridanus_sdss.py
```

This will download and filter the sample, and output a catalog of positions and masses.

2. **Run the density estimation**:

```bash
python Density_Estimation_Wavelet_SPH.py
```

This script takes the galaxy sample and produces a radial density profile \(\rho(r)\), saved in `.csv` and plotted automatically.

---

## 🧪 Output

- `density_profile.csv` — Compressed radial bins with \(\rho(r)\)
- `density_profile_plot.png` — Smoothed plot for visual inspection

---

## 📌 Notes

- These scripts are part of the **Elastic Spacetime Diagnostics** developed for the Eridanus Supervoid.
- All results are used in the paper:  
  *"Elastic Dynamics in Voids: Visualization of D and D′ Operators in Underdense Cosmology"*

---

## 🤝 Attribution

If you use these scripts, please cite the GitHub repository:  
[https://github.com/LeonardoSeriacopi/D_Dprime_Eridanus](https://github.com/LeonardoSeriacopi/D_Dprime_Eridanus)
