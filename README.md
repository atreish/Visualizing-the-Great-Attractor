# 🌌 Visualizing the Great Attractor: Galaxy Infall & Peculiar Velocity Field Mapping

This project models and visualizes the large-scale **galactic motion toward the Great Attractor**, a mysterious gravitational anomaly in the observable universe. By combining **real astronomical data** from surveys like **2MASS** and **SDSS** (via `astroquery`) with **simulated or observational peculiar velocity fields**, the project generates an interactive, vector-based 3D map of galactic infall.

It blends **astrophysics**, **dynamical systems**, and **data science** to better understand the cosmic structure and influence of the Great Attractor.

---

## 🚀 Features

- Pulls real galaxy data near the Great Attractor using **astroquery** (SIMBAD, VizieR, IRSA)
- Converts RA/Dec + redshift into 3D Cartesian coordinates
- Simulates galaxy **peculiar velocities** based on gravitational infall models
- Visualizes galaxy positions and vector fields in 3D using **Matplotlib** or **Plotly**
- Modular codebase for easy integration of observational peculiar velocity datasets (e.g., Cosmicflows-3)

---

## 📁 Project Structure

```
great_attractor/
├── 01_data/              # Cleaned or cached datasets
├── 02_analysis/          # Scripts for querying, converting, simulating
├── 03_visualization/     # 3D plotting and animations
├── notebooks/            # Jupyter notebook for exploration
├── requirements.txt
└── README.md
```

---

## 🔬 Scientific Concepts Used

- Hubble Flow & Peculiar Velocity Deviation  
- Dynamical Systems & Infall Modeling  
- Redshift-to-Distance Conversion  
- Gravitational Center Estimation  
- Vector Field Visualization in 3D Space  

---

## 📦 Dependencies

- `astroquery`
- `astropy`
- `pandas`
- `numpy`
- `matplotlib`
- `scipy`
- `plotly`

Install with:

```bash
pip install -r requirements.txt
```

---

## 📊 How It Works

1. **Query Nearby Galaxies**  
   Using `astroquery`, galaxies near the Great Attractor are pulled from catalogs such as VizieR and SIMBAD.

2. **Coordinate Transformation**  
   Galaxies' RA/Dec + redshift are converted to 3D Cartesian coordinates using `astropy.coordinates`.

3. **Velocity Field Simulation**  
   A gravitational infall model estimates galaxy motion toward a central attractor. Real peculiar velocities can be integrated if available.

4. **3D Vector Field Plotting**  
   Positions and velocities are plotted as quiver vectors in 3D space to illustrate infall dynamics.

---

## 🧠 Motivation

This project is part of a portfolio created in preparation for a PhD in mathematics focused on **celestial mechanics**, **cosmic web modeling**, and **relativistic dynamics**. It demonstrates a blend of **advanced mathematical modeling**, **astrophysical insight**, and **Python-based scientific computing**.

---

## 📜 Citation

- Cosmicflows-3: Tully et al. (2016), AJ 152, 50
- [https://arxiv.org/abs/1605.01765](https://arxiv.org/abs/1605.01765)

---

## 🧑‍💻 Author

Atreish Ramlakhan — [atreishramlakhan@gmail.com](mailto:atreishramlakhan@gmail.com)  
GitHub: [https://github.com/atreish](https://github.com/atreish)

