
# Diffraction Applet (2D)

This repository contains an interactive Jupyter/Voila applet for visualizing 2D real-space lattice structures and their corresponding discrete diffraction patterns.

## Features
- Adjustable unit-cell parameters: **a**, **b**, **γ**
- Editable fractional atomic positions
- Real-space visualization over a **3×3 tiled unit-cell**
- Discrete reciprocal-space reflections (intensity and phase)
- Toggle atom 1 on/off
- Fully interactive Plotly figures

## Launch (Binder + Voila)
Click below to run the applet in your browser:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/eriksvenssongrape/diffraction-applet-discrete/main?urlpath=voila/render/diffraction-applet-discrete.ipynb)


## Run Locally
Clone the repository:
```
git clone https://github.com/eriksvenssongrape/diffraction-applet-discrete.git
cd diffraction-applet-discrete
```

Install dependencies:
```
pip install -r requirements.txt
```

Run the notebook:
```
jupyter notebook
```
or launch using Voila:
```
voila diffraction-applet-discrete.ipynb
```

## Contents
- `diffraction-applet-discrete.ipynb` — main interactive applet
- `requirements.txt` — environment specification
- `README.md` — project overview
