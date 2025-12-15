# QSphericalStats: Spherical Statistics in QGIS

<p align="center">
  <img src="https://github.com/mhaut/QgisSphericalStats3D/blob/main/images/logo.png?raw=true" width="450">
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

> ⚠️ **Important**
> This plugin is **not published in the official QGIS Plugin Repository**, so it will **not appear in the QGIS Plugin Manager search list**.
> Installation must be done **manually**, either from a ZIP file or by cloning the repository.

---

### ✔️ Option 1: Install from ZIP (recommended)

1. Download the ZIP file from GitHub:
   **Code → Download ZIP**

2. Open **QGIS**

3. Go to:
   ```
   Plugins → Manage and Install Plugins → Install from ZIP
   ```

4. Select the downloaded `QSphericalStats.zip` file

5. Click **Install Plugin**

6. Restart QGIS if the plugin does not appear immediately

---

### ✔️ Option 2: Install from source (Git clone)

#### 1️⃣ Go to the QGIS plugins directory

**Linux (Ubuntu):**
```bash
cd ~/.local/share/QGIS/QGIS3/profiles/default/python/plugins
```

**Windows:**
```text
C:\Users\YOUR_USER\AppData\Roaming\QGIS\QGIS3\profiles\default\python\plugins
```

**macOS:**
```bash
cd ~/Library/Application\ Support/QGIS/QGIS3/profiles/default/python/plugins
```

---

#### 2️⃣ Clone the repository

```bash
git clone https://github.com/mhaut/QSphericalStats.git
```

---

#### 3️⃣ Enable the plugin in QGIS

1. Open **QGIS**
2. Go to **Plugins → Manage and Install Plugins**
3. Search for **QSphericalStats**
4. Enable the plugin

---

## Troubleshooting

If the plugin does not load, verify that the folder structure is:

```
QSphericalStats/
├── __init__.py
├── metadata.txt
├── q_spherical_stats.py
└── ...
```

You can also check error messages in:

```
Plugins → Python Console → Show Log Messages
```

---

## License

This project is released under an open-source license.
See the `LICENSE` file for details.

---

## Acknowledgements

- **PySphericalStats** for providing the scientific foundation for spherical statistical analysis
- The **QGIS** open-source community
