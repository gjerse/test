# Metis Tutorial ISRO_ESA workshop January 2026, India

**Exploring Metis Data within the SunPy Ecosystem**

This Data Analysis Tutorial for Metis will guide you through getting hold of Metis data from the ESA Solar Orbiter Archive (SOAR). We will describe the different types of Metis Level-2 data products, how to visualize them, and how to build multi-instrument composites.

---
**Run in Binder**

This notebook can be run online in Colav without any local installation. It’s the fastest way to get started:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ISRO-ESA-Heliophysics-Workshop/hands-on-materials/blob/main/solar-orbiter/metis/Metis_ISRO_ESA_DataWorkshop.ipynb)
 
---
**Prerequisites**

The notebook relies on the standard Solar Physics Python stack. Python 3.9+ is recommended with the following packages:

- sunpy, sunpy-soar, astropy, matplotlib, numpy, drms, zeep, cmcrameri, scipy, ipython, jupyterlab

---
**Installation & Setup**

1. Install via pip
You can install the necessary requirements using:
``` bash
pip install sunpy[all] sunpy-soar astropy matplotlib numpy drms zeep cmcrameri scipy jupyterlab
```   


3. Get the **MetisMap**
Clone the repository containing the Metis Map to your local machine:

``` bash
git clone https://github.com/gjerse/metisRepo.git

``` 

**How to Run**

- Open your terminal or Anaconda prompt.

- Navigate to the folder containing the file Exploring_Metis_Data.ipynb.

- Launch Jupyter Lab or Notebook:

``` bash
jupyter lab Exploring_Metis_Data.ipynb
``` 
<jupyter lab Exploring_Metis_Data.ipynb>

Run the cells sequentially to perform the data discovery, processing, and visualization.
