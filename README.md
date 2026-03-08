<p align="center">
  <img src="https://img.shields.io/badge/🇹🇿_Tanzania-Ethnic_Groups-blue?style=for-the-badge&labelColor=1a9f29" alt="Tanzania Ethnic Groups"/>
</p>

<h1 align="center">🗺️ Tanzania Ethnicity Shapefile</h1>

<p align="center">
  <strong>Geospatial dataset mapping ethnic group boundaries across Tanzania</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/QGIS-3.x-93b023?style=flat-square&logo=qgis&logoColor=white" alt="QGIS"/>
  <img src="https://img.shields.io/badge/ArcGIS-Compatible-2C7AC3?style=flat-square&logo=arcgis&logoColor=white" alt="ArcGIS"/>
  <img src="https://img.shields.io/badge/Format-ESRI_Shapefile-FF6F00?style=flat-square" alt="Shapefile"/>
  <img src="https://img.shields.io/badge/CRS-WGS_84-red?style=flat-square" alt="CRS"/>
  <img src="https://img.shields.io/badge/Geometry-Polygon-9C27B0?style=flat-square" alt="Polygon"/>
  <img src="https://img.shields.io/badge/License-Open_Data-green?style=flat-square" alt="License"/>
  <img src="https://img.shields.io/github/repo-size/Heed725/Tanzania_Ethnicity_Shapefile?style=flat-square&label=Size" alt="Repo Size"/>
  <img src="https://img.shields.io/github/stars/Heed725/Tanzania_Ethnicity_Shapefile?style=flat-square&logo=github" alt="Stars"/>
  <img src="https://img.shields.io/github/last-commit/Heed725/Tanzania_Ethnicity_Shapefile?style=flat-square" alt="Last Commit"/>
</p>

---

<p align="center">

  <a href="https://github.com/Heed725/Tanzania_Ethnicity_Shapefile/archive/refs/heads/main.zip">
    <img src="https://img.shields.io/badge/⬇️_DOWNLOAD_ZIP-All_Files-2ea44f?style=for-the-badge" alt="Download ZIP"/>
  </a>
  &nbsp;&nbsp;
  <a href="https://github.com/Heed725/Tanzania_Ethnicity_Shapefile/raw/main/Tanzania_Ethnic_Groups.shp">
    <img src="https://img.shields.io/badge/⬇️_Download-.SHP-orange?style=for-the-badge" alt="Download SHP"/>
  </a>
  &nbsp;&nbsp;
  <a href="https://github.com/Heed725/Tanzania_Ethnicity_Shapefile/raw/main/Tanzania_Ethnic_Groups.dbf">
    <img src="https://img.shields.io/badge/⬇️_Download-.DBF-orange?style=for-the-badge" alt="Download DBF"/>
  </a>

</p>

<p align="center">

  <a href="https://github.com/Heed725/Tanzania_Ethnicity_Shapefile/raw/main/Tanzania_Ethnic_Groups.shx">
    <img src="https://img.shields.io/badge/⬇️_Download-.SHX-blue?style=flat-square" alt="Download SHX"/>
  </a>
  &nbsp;
  <a href="https://github.com/Heed725/Tanzania_Ethnicity_Shapefile/raw/main/Tanzania_Ethnic_Groups.prj">
    <img src="https://img.shields.io/badge/⬇️_Download-.PRJ-blue?style=flat-square" alt="Download PRJ"/>
  </a>
  &nbsp;
  <a href="https://github.com/Heed725/Tanzania_Ethnicity_Shapefile/raw/main/Tanzania_Ethnic_Groups.cpg">
    <img src="https://img.shields.io/badge/⬇️_Download-.CPG-blue?style=flat-square" alt="Download CPG"/>
  </a>
  &nbsp;
  <a href="https://github.com/Heed725/Tanzania_Ethnicity_Shapefile/raw/main/Tanzania_Ethnic_Groups.qmd">
    <img src="https://img.shields.io/badge/⬇️_Download-.QMD-blue?style=flat-square" alt="Download QMD"/>
  </a>

</p>

> **💡 Recommended:** Use the **Download ZIP** button above to get all files at once. All shapefile components must be in the same folder to work correctly.

---

## 📋 Overview

An ESRI Shapefile dataset representing the **spatial distribution of ethnic groups across Tanzania**. The dataset contains polygon geometries delineating the geographic areas associated with different ethnic communities in the United Republic of Tanzania — home to over **120 ethnic groups**, one of the most ethnically diverse nations in Africa.

---

## 📁 File Structure

All files share the base name `Tanzania_Ethnic_Groups` and **must remain in the same directory**:

```
Tanzania_Ethnicity_Shapefile/
│
├── Tanzania_Ethnic_Groups.shp   ← 🔷 Geometry (polygon boundaries)
├── Tanzania_Ethnic_Groups.shx   ← 🔷 Spatial index
├── Tanzania_Ethnic_Groups.dbf   ← 🔷 Attribute table (ethnic group names & data)
├── Tanzania_Ethnic_Groups.prj   ← 🔷 Coordinate Reference System (WGS 84)
├── Tanzania_Ethnic_Groups.cpg   ← ⬜ Character encoding
├── Tanzania_Ethnic_Groups.qmd   ← ⬜ QGIS layer metadata
└── README.md                    ← 📄 This file
```

🔷 = **Required** (shapefile won't load without these) &nbsp;&nbsp; ⬜ = Optional but recommended

| Extension | Purpose | Required? |
|-----------|---------|:---------:|
| `.shp` | Stores the polygon geometry for each ethnic group boundary | ✅ Yes |
| `.shx` | Index file linking each geometry to its attribute record | ✅ Yes |
| `.dbf` | dBASE table with attribute data (group names, codes, etc.) | ✅ Yes |
| `.prj` | Defines the coordinate reference system (CRS) | ✅ Critical |
| `.cpg` | Specifies text encoding (e.g., UTF-8) for the `.dbf` | ⬜ Recommended |
| `.qmd` | QGIS-specific layer metadata | ⬜ Optional |

---

## 🖥️ Software Compatibility

| Software | Version | Type |
|----------|---------|------|
| ![QGIS](https://img.shields.io/badge/-QGIS_3.x+-93b023?style=flat-square&logo=qgis&logoColor=white) | 3.0+ | Free & Open Source |
| ![ArcGIS](https://img.shields.io/badge/-ArcGIS_Pro_2.x+-2C7AC3?style=flat-square) | 2.0+ | Commercial |
| ![GDAL](https://img.shields.io/badge/-GDAL/OGR_3.x+-339933?style=flat-square) | 3.0+ | Command Line |
| ![Python](https://img.shields.io/badge/-GeoPandas_0.9+-3776AB?style=flat-square&logo=python&logoColor=white) | 0.9+ | Python Library |
| ![R](https://img.shields.io/badge/-R_sf_package-276DC3?style=flat-square&logo=r&logoColor=white) | 1.0+ | R Library |
| ![Google Earth](https://img.shields.io/badge/-Google_Earth_Pro-4285F4?style=flat-square&logo=googleearth&logoColor=white) | Any | Free (convert to KML first) |

---

## 📥 How to Download

### Option 1 — Download Everything (Recommended)

<a href="https://github.com/Heed725/Tanzania_Ethnicity_Shapefile/archive/refs/heads/main.zip">
  <img src="https://img.shields.io/badge/⬇️_DOWNLOAD_FULL_ZIP-2ea44f?style=for-the-badge" alt="Download ZIP"/>
</a>

Or via terminal:

```bash
git clone https://github.com/Heed725/Tanzania_Ethnicity_Shapefile.git
```

### Option 2 — Download from GitHub UI

1. Click the green **`<> Code`** button at the top of this repository
2. Select **Download ZIP**
3. Extract the ZIP to your working folder

---

## 🗺️ How to Import & Use

### QGIS (Recommended)

#### Method 1 — Drag and Drop

1. Open **QGIS**
2. Locate `Tanzania_Ethnic_Groups.shp` in your file manager
3. **Drag** it directly into the QGIS map canvas
4. Done — the layer loads instantly

#### Method 2 — Add Vector Layer

1. Go to **Layer** → **Add Layer** → **Add Vector Layer** (`Ctrl+Shift+V`)
2. Set Source Type to **File**
3. Click **Browse (...)** → select `Tanzania_Ethnic_Groups.shp`
4. Click **Add** → **Close**

#### Method 3 — Browser Panel

1. Open the **Browser Panel** (View → Panels → Browser)
2. Navigate to your folder
3. Double-click `Tanzania_Ethnic_Groups.shp`

### ArcGIS Pro

1. Open or create a project in ArcGIS Pro
2. In the **Catalog Pane**, browse to the shapefile folder
3. Drag `Tanzania_Ethnic_Groups.shp` onto the map
4. Or right-click → **Add To Current Map**

### Python (GeoPandas)

```python
import geopandas as gpd
import matplotlib.pyplot as plt

# Load shapefile
tz_ethnic = gpd.read_file("Tanzania_Ethnic_Groups.shp")

# Explore the data
print(tz_ethnic.head())
print(f"Number of ethnic groups: {len(tz_ethnic)}")
print(f"Columns: {list(tz_ethnic.columns)}")
print(f"CRS: {tz_ethnic.crs}")
print(f"Bounds: {tz_ethnic.total_bounds}")

# Visualize
fig, ax = plt.subplots(1, 1, figsize=(10, 12))
tz_ethnic.plot(ax=ax, edgecolor="black", linewidth=0.3, cmap="Set3")
ax.set_title("Ethnic Groups of Tanzania")
plt.tight_layout()
plt.savefig("tanzania_ethnic_map.png", dpi=200)
plt.show()
```

### R

```r
library(sf)
library(ggplot2)

tz_ethnic <- st_read("Tanzania_Ethnic_Groups.shp")
summary(tz_ethnic)

ggplot(tz_ethnic) +
  geom_sf(aes(fill = NAME), show.legend = FALSE) +
  theme_minimal() +
  labs(title = "Ethnic Groups of Tanzania")
```

### GDAL / OGR (Command Line)

```bash
# View metadata and field names
ogrinfo -so Tanzania_Ethnic_Groups.shp Tanzania_Ethnic_Groups

# Convert to GeoJSON
ogr2ogr -f "GeoJSON" tanzania_ethnic.geojson Tanzania_Ethnic_Groups.shp

# Convert to KML (for Google Earth)
ogr2ogr -f "KML" tanzania_ethnic.kml Tanzania_Ethnic_Groups.shp

# Convert to GeoPackage
ogr2ogr -f "GPKG" tanzania_ethnic.gpkg Tanzania_Ethnic_Groups.shp
```

---

## 🎨 Styling Tips in QGIS

Since this repository doesn't include a `.qml` style file, here's how to create a categorized map:

1. Right-click the layer → **Properties** → **Symbology**
2. Change the renderer from *Single Symbol* to **Categorized**
3. Set the **Column** to the ethnic group name field
4. Click **Classify** to generate unique colors for each group
5. Adjust colors as needed → **OK**

**Save your style for reuse:**
- In Symbology, click **Style** (bottom-left) → **Save Style...**
- Save as `.qml` in the same folder as the shapefile

**Pro tip:** Use the *Spectral* or *Set3* color ramp for good visual distinction between groups.

---

## 💡 Use Cases

| Domain | Application |
|--------|-------------|
| **Ethnography** | Mapping the distribution of Tanzania's 120+ ethnic communities |
| **Linguistics** | Correlating ethnic boundaries with Bantu, Nilotic, Cushitic, and Khoisan language zones |
| **History** | Analyzing pre-colonial tribal territories and post-independence migrations |
| **Demographics** | Overlaying with census and population density data |
| **Public Health** | Understanding culturally specific health practices by region |
| **Education** | Teaching GIS, African studies, and cultural geography |
| **Development** | Supporting culturally sensitive planning and resource allocation |
| **Conflict Studies** | Analyzing intergroup dynamics and land-use patterns |

---

## 🔧 Troubleshooting

| Problem | Solution |
|---------|----------|
| **Layer won't load** | Ensure `.shp`, `.shx`, and `.dbf` are all in the same folder |
| **Layer appears in wrong location** | Check that `.prj` file is present; set project CRS to EPSG:4326 (WGS 84) |
| **Garbled text in attributes** | Ensure `.cpg` file is present alongside the shapefile |
| **"Layer is not valid" error** | Re-download all files — one may be corrupted or incomplete |
| **No features visible** | Zoom to layer extent: right-click layer → **Zoom to Layer** |
| **Want to convert format** | Use `ogr2ogr` commands above to export as GeoJSON, KML, or GeoPackage |

---

## 🤝 Contributing

Contributions, fixes, and improvements are welcome!

1. **Fork** the repository
2. Create a branch: `git checkout -b feature/my-improvement`
3. Commit changes: `git commit -m "Describe your change"`
4. Push: `git push origin feature/my-improvement`
5. Open a **Pull Request**

Ideas for contributions: add a `.qml` style file, improve attribute data, add metadata, or provide sample maps.

---

## 🔗 Related Repositories

| Repository | Description |
|------------|-------------|
| [Africa_Ethnic_Groups](https://github.com/Heed725/Africa_Ethnic_Groups) | Ethnic group shapefile for the entire African continent |

---

## 🔗 Useful Resources

- [QGIS Documentation](https://docs.qgis.org/)
- [Tanzania National Bureau of Statistics](https://www.nbs.go.tz/)
- [GREG — Geo-referencing of Ethnic Groups (ETH Zurich)](https://icr.ethz.ch/data/greg/)
- [Africa GeoPortal — Esri](https://www.africageoportal.com/)
- [openAFRICA Data Portal](https://open.africa/)

---

## 📝 License

This dataset is shared for educational and research purposes. Attribution is appreciated. Please verify licensing terms before commercial use.

---

<p align="center">
  <img src="https://img.shields.io/badge/Made_in-Tanzania_🇹🇿-1a9f29?style=for-the-badge" alt="Made in Tanzania"/>
  &nbsp;
  <img src="https://img.shields.io/badge/Built_with-QGIS-93b023?style=for-the-badge&logo=qgis&logoColor=white" alt="Built with QGIS"/>
  &nbsp;
  <img src="https://img.shields.io/badge/Open-GIS_Data-blue?style=for-the-badge" alt="Open GIS Data"/>
</p>

<p align="center">
  <sub>⭐ If you find this dataset useful, please consider giving it a star!</sub>
</p>
