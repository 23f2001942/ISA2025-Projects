# 🌌 Cosmic Parameters Insights — ISA 2025 Astrophysics Projects

This repository contains Python notebooks, datasets, and final reports for two astrophysics research projects completed as part of the **India Space Academy (ISA) 2025 Summer School**. These projects explore the dynamical mass of galaxy clusters and the estimation of cosmological parameters using real observational data from SDSS and Pantheon+SH0ES datasets.

---

## 🧠 Projects Overview

### 1️⃣ Estimating the Dynamical Mass of a Galaxy Cluster

- **Objective:** Determine the mass of a galaxy cluster using spectroscopic redshift data from SDSS.
- **Approach:**
  - Filter cluster members using redshift dispersion (±3σ).
  - Calculate cluster velocity dispersion and physical size.
  - Apply the virial theorem to estimate dynamical mass.
  - Compare luminous vs. dynamical mass to infer dark matter presence.
- **Result:** Mass-to-light ratio ~136, confirming a dominant dark matter component.

### 2️⃣ Estimating Cosmological Parameters from Type Ia Supernovae

- **Objective:** Estimate the Hubble constant (H₀), matter density (Ωₘ), and universe age using Type Ia supernovae.
- **Approach:**
  - Use the Pantheon+SH0ES dataset.
  - Fit a flat ΛCDM cosmological model using non-linear least squares.
  - Analyze residuals and redshift-dependent trends.
  - Explore the effect of Ωₘ on H₀ and the age of the universe.
- **Result:** Estimated H₀ = 72.97 ± 0.26 km/s/Mpc, age ≈ 12.36 Gyr. Results align with late-universe measurements and contribute to the Hubble tension discussion.

---

## ⚙️ Requirements

Make sure you have Python 3.8+ and the following libraries installed:

```bash
pip install numpy pandas matplotlib scipy astropy
```

---

## 📊 Sample Visualizations

- 📈 Redshift histograms and velocity dispersion plots for galaxy clusters.
- 🌌 Hubble diagram and residuals for supernova-based cosmology fits.
- 📋 Tables showing how H₀ and universe age vary with Ωₘ.

---

## 🧾 Certification

This work was conducted under the guidance of Mr. Sahil Sakkarwal, India Space Academy, and officially certified as part of the ISA 2025 Summer School on Astronomy and Astrophysics.

--- 

## 👤 Author

- Shamanthak Reddy Mallu
- BITS Pilani Hyderabad Campus
- ISA Admission Number : 554265

---

## 🙌 Acknowledgments

- 🛰️ India Space Academy (ISA) for organizing the Summer School and providing datasets
- 🔭 Sloan Digital Sky Survey (SDSS) for galaxy data
- 🌠 Pantheon+SH0ES Collaboration for supernovae data and cosmology resources






