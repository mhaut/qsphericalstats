# QSphericalStats: Spherical Statistics in QGIS

<p align="center">
<img src="https://github.com/mhaut/QgisSphericalStats3D/blob/main/images/logo.png?raw=true" width="600">
</p>

## Overview

**QSphericalStats** is an open-source **QGIS plugin** that provides tools for performing **spherical statistics** on 3D directional data.  
It extends QGIS with capabilities to analyze **orientations, angular distributions, concentration, vector modules**, and density plots directly from geospatial datasets.

This plugin is based on the scientific library **PySphericalStats** and brings rigorous spherical statistical methods into a user-friendly GIS environment.

Typical applications include:

- Comparing DEMs (LiDAR, ASTER, etc.)  
- Analyzing slope orientations and 3D surface morphology  
- 3D geospatial feature orientation studies  
- Environmental and geomorphological analysis  
- Geological and structural vector data  

---

## Installation

### ✔️ Install from QGIS Plugin Manager (recommended)
*(When the plugin is published in the QGIS repository)*  
1. Open **QGIS**
2. Go to **Plugins → Manage and Install Plugins**
3. Search for **QSphericalStats**
4. Click **Install**

### ✔️ Install manually from source

```bash
git clone https://github.com/mhaut/QSphericalStats
cd QSphericalStats
