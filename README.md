<p align="center">
  <a href="https://github.com/awesome-spectral-indices/awesome-ASI"><img src="https://github.com/awesome-spectral-indices/awesome-ASI/raw/main/awesome-asi.png" alt="Awesome Spectral Indices"></a>
</p>
<p align="center">
    <em>A curated list of Awesome Spectral Indices (ASI) resources</em>
</p>
<p align="center">
<a href="https://awesome.re" target="_blank">
    <img src="https://awesome.re/badge.svg" alt="Awesome">
</a>
</p>

## Table of Contents

- [Official Resources](#official-resources)
- [Python](#python)
- [R](#r)
- [Google Earth Engine](#google-earth-engine)
- [Apps](#apps)
- [YouTube](#youtube)
- [Tutorials](#tutorials)
- [Podcasts](#podcasts)
- [Blogs](#blogs)
- [Datasets](#datasets)
- [Papers](#papers)
- [Attribution](#attribution)

-----------------------------------

## Official Resources

- [Awesome Spectral Indices](https://github.com/awesome-spectral-indices/awesome-spectral-indices) - Official GitHub Repository
- [Espectro](https://github.com/awesome-spectral-indices/espectro) - Official Streamlit Web App [![Espectro](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://share.streamlit.io/davemlz/espectro/main/espectro.py)
- [spectral](https://github.com/awesome-spectral-indices/spectral) - Official Google Earth Engine Module
- [spyndex](https://github.com/awesome-spectral-indices/spyndex) - Official Python Package

-----------------------------------

## Python

- [eoreader](https://github.com/sertit/eoreader) - Remote-sensing opensource python library reading optical and SAR sensors, loading and stacking bands, clouds, DEM and spectral indices in a sensor-agnostic way.
- [openeo-python-client](https://github.com/Open-EO/openeo-python-client) - Python client API for OpenEO. ASI provided as experimental feature.
- [spyndex](https://github.com/awesome-spectral-indices/spyndex) - Official ASI Python Package. Spectral Indices can be computed for Python objects with third party libraries (e.g., `numpy`, `pandas`, `xarray`, `dask`).

-----------------------------------

## R

- [rgeeExtra](https://github.com/r-earthengine/rgeeExtra) - An R package for high-level functions to process spatial and simple Earth Engine objects. ASI is available through the `spectralIndices()` function.

-----------------------------------

## Google Earth Engine

### Python

- [eeExtra](https://github.com/r-earthengine/ee_extra) - A ninja Python package that unifies the Google Earth Engine ecosystem. Provides ASI methods for `eemont` and `rgeeExtra`.
- [eemont](https://github.com/davemlz/eemont) - A Python package that extends Google Earth Engine. ASI is available through the `spectralIndices()` method.
- [spyndex](https://github.com/awesome-spectral-indices/spyndex) - Official ASI Python Package. Spectral Indices can be computed for Google Earth Engine objects.

### JavaScript

- [spectral](https://github.com/awesome-spectral-indices/spectral) - Official ASI Google Earth Engine Module. Deploys ASI for the Code Editor.

### R

- [rgeeExtra](https://github.com/r-earthengine/rgeeExtra) - An R package for high-level functions to process spatial and simple Earth Engine objects. ASI is available through the `spectralIndices()` function.

-----------------------------------

## Apps

### Streamlit

- [Espectro](https://github.com/awesome-spectral-indices/espectro) - Official Streamlit Web App GitHub Repository [![Espectro](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://share.streamlit.io/davemlz/espectro/main/espectro.py)

### Visualization

- [LexCube](https://www.lexcube.org/?!s2flx_sen2flux_de-hai_l3a/kndvi/0-194/0-510/0-510) - Leipzig Explorer of Earth Data Cubes. Provides an interactive ASI example for a Sentinel-2 data cube.

### Miscellaneous

- [openEO Web Editor](https://github.com/Open-EO/openeo-web-editor) - Web-based UI for OpenEO. A wizard provides an easy way to generate products based on ASI.

-----------------------------------

## YouTube

### Google Earth Engine

- [ktmagar's YT | Awesome Spectral Indices in Earth Engine](https://www.youtube.com/watch?v=GJuoBp6B3fU&ab_channel=ktmagar%27sYT)
- [Open Source Remote Sensing & GIS | GEE tutorial 3: Compute multiple spectral indices easily in Google Earth Engine](https://www.youtube.com/watch?v=b7lCNNJOfZY&ab_channel=OpenSourceRemoteSensing%26GIS)
- [geodose video | How to Calculate Various Spectral Indices in Google Earth Engine Quickly](https://www.youtube.com/watch?v=Vkx-mh6Wr50&ab_channel=geodosevideo)
- [MasterGIS | MasterGIS Days 2021 🌎: Procesamiento y visualización de datos geoespaciales con GEE](https://youtu.be/MU28078U14Y?t=1641) [Spanish]

### Miscellaneous

- [openEO | openEO Web Editor Wizard](https://www.youtube.com/watch?v=iAmybwE425k&ab_channel=openEO)

-----------------------------------

## Tutorials

### Python

- [David Montero Loaiza | Python Built-in Types](https://spyndex.readthedocs.io/en/latest/tutorials/python_builtin.html)
- [David Montero Loaiza | Numpy](https://spyndex.readthedocs.io/en/latest/tutorials/numpy.html)
- [David Montero Loaiza | Pandas](https://spyndex.readthedocs.io/en/latest/tutorials/pandas.html)
- [David Montero Loaiza | Xarray](https://spyndex.readthedocs.io/en/latest/tutorials/xarray.html)
- [David Montero Loaiza | Geopandas](https://spyndex.readthedocs.io/en/latest/tutorials/geopandas.html)
- [David Montero Loaiza | Dask](https://spyndex.readthedocs.io/en/latest/tutorials/dask.html)
- [David Montero Loaiza | Earth Engine](https://spyndex.readthedocs.io/en/latest/tutorials/ee.html)
- [David Montero Loaiza | Planetary Computer](https://spyndex.readthedocs.io/en/latest/tutorials/pc.html)

### Google Earth Engine

#### Python

- [David Montero Loaiza | Computing Spectral Indices in Landsat 8](https://eemont.readthedocs.io/en/latest/tutorials/004-Computing-Spectral-Indices-Landsat-8.html)
- [David Montero Loaiza | Computing Spectral Indices for MODIS](https://eemont.readthedocs.io/en/latest/tutorials/012-Spectral-Indices-MODIS-MOD09GA.html)
- [David Montero Loaiza | Spectral Indices From the Awesome Spectral Indices for GEE](https://eemont.readthedocs.io/en/latest/tutorials/016-Spectral-Indices-From-Awesome-Spectral-Indices-List.html)
- [David Montero Loaiza | Access to Awesome Spectral Indices v0.0.3](https://eemont.readthedocs.io/en/latest/tutorials/030-Awesome-Spectral-Indices-v003.html)
- [David Montero Loaiza | Monthly Global kNDVI using eemont and wxee](https://eemont.readthedocs.io/en/latest/tutorials/032-Combining-eemont-wxee.html)
- [David Montero Loaiza | Landsat-9](https://eemont.readthedocs.io/en/latest/tutorials/035-Landsat-9.html)
- [Aaron Zuspan | Combining wxee and eemont](https://wxee.readthedocs.io/en/latest/examples/eemont.html)

#### JavaScript

- [David Montero Loaiza | Example 1: Exploring spectral indices](https://code.earthengine.google.com/6f438f939672318555b8e1ae55257020)
- [David Montero Loaiza | Example 2: Computing One Index](https://code.earthengine.google.com/378462b0d7b6dd8e523e02b349e67508)
- [David Montero Loaiza | Example 3: Computing Multiple Indices](https://code.earthengine.google.com/94523fdbc4ff80b77e76e7c05983c276)
- [David Montero Loaiza | Example 4: Computing Kernel Indices](https://code.earthengine.google.com/45399b947d0b1db532f1d2e6dd86d42a)
- [David Montero Loaiza | Example 5: Mapping Indices Over an Image Collection](https://code.earthengine.google.com/9c303e11f1c4a04a1c9c2dfbeaf2abee)

-----------------------------------

## Podcasts

- [Scene From Above | S11E2: Disruption](https://scenefromabove.podbean.com/e/s11e2-disruption/)

-----------------------------------

## Blogs

- [geodose | How to Calculate Various Spectral Indices in Google Earth Engine Quickly](https://www.geodose.com/2022/10/how-to-calculate-various-spectral-indices-gee-quick.html)
- [Akis Karagiannis | Spectral Reflectance Newsletter #5
](https://medium.com/spectral-reflectance/spectral-reflectance-newsletter-5-e38d99fd582a)
- [scicrop | O uso dos índices vegetativos e do sensoriamento remoto na agricultura](https://scicrop.com/2022/03/01/o-uso-dos-indices-vegetativos-e-do-sensoriamento-remoto-na-agricultura/) [Portuguese]

-----------------------------------

## Datasets

- [UniNa - Machine Learning 22/23 - MiniContest n1 | Above Ground Biomass estimation from Sentinel-2](https://www.kaggle.com/competitions/unina-machine-learning-2223/data)

-----------------------------------

## Papers

### Official Papers

- [spectral: Awesome Spectral Indices deployed via the Google Earth Engine JavaScript API](https://doi.org/10.5194/isprs-archives-XLVIII-4-W1-2022-301-2022) - **How to cite.** Montero, D., Aybar, C., Mahecha, M. D., and Wieneke, S.: SPECTRAL: AWESOME SPECTRAL INDICES DEPLOYED VIA THE GOOGLE EARTH ENGINE JAVASCRIPT API, Int. Arch. Photogramm. Remote Sens. Spatial Inf. Sci., XLVIII-4/W1-2022, 301–306, https://doi.org/10.5194/isprs-archives-XLVIII-4-W1-2022-301-2022, 2022.

### ASI Citations

- [Deep Learning on Synthetic Data Enables the Automatic
Identification of Deficient Forested Windbreaks in the
Paraguayan Chaco](https://doi.org/10.3390/rs14174327) - **How to cite.** Kriese, J.; Hoeser, T.; Asam, S.; Kacic, P.; Da Ponte, E.; Gessner, U. Deep Learning on Synthetic Data Enables the Automatic Identification of Deficient Forested Windbreaks in the Paraguayan Chaco. Remote Sens. 2022, 14, 4327. https://doi.org/10.3390/rs14174327
- [BUSINESS INTELLIGENCE THROUGH MACHINE LEARNING FROM SATELLITE REMOTE SENSING DATA](https://ir.lib.uth.gr/xmlui/bitstream/handle/11615/59406/25458.pdf) - **How to cite.** Kyriakos, C. 2022. BUSINESS INTELLIGENCE THROUGH MACHINE LEARNING FROM SATELLITE REMOTE SENSING DATA. Diploma Thesis, University of Thessaly.

-----------------------------------

## Attribution

The repository banner was created on top of [this photo](https://www.pexels.com/es-es/foto/luces-oscuro-colorido-arcoiris-11734794/) by [Evie Shaffer](https://www.pexels.com/es-es/@evie-shaffer-1259279/).
