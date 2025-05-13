# Liquid Biopsy 3D Simulation

This Jupyter notebook contains an interactive 3D simulation of how 
Positive Predictive Value (PPV) in cancer screening tests is affected by:

- Sensitivity
- Specificity
- Disease Prevalence

The simulation allows you to visualize PPV as a 3D surface that changes dynamically with prevalence using a slider. It helps illustrate the trade-offs in diagnostic screening, especially in low-prevalence settings.

## How to run it

You can run the notebook via [Binder](https://mybinder.org):

1. Upload the following files to a public GitHub repository:
    - `Liquid_Biopsy_3D.ipynb`
    - `requirements.txt`
    - `README.md`

2. Go to [https://mybinder.org](https://mybinder.org)

3. Enter your GitHub repository URL

4. Set the file to open: `Liquid_Biopsy_3D.ipynb`

5. Click **Launch** and interact with the 3D simulation!

## Example

The notebook uses Plotly to create a 3D surface of PPV values with:
- X-axis: Sensitivity
- Y-axis: Specificity
- Z-axis: PPV

Prevalence is controlled via a slider (ipywidgets).