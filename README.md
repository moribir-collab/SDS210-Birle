# Urban Heat and Vegetation Change in Zurich, 1985–2024

SDS210 Programming with Spatial Data — Project 3: Urban Heat

## Repository contents

- `urban_heat_zurich.ipynb` — fully executed Jupyter Notebook
- `Report_Birle_SDS210.pdf` — project report
- `README.md` — this file

## Data

The 14 Landsat composite files for Zurich (1985–2024) are available on the
course server under `course/sds210/data/projects/project_3/`. Each file is
named `LandsatComposite_Zurich_YYYY.tif` and contains 7 spectral bands.

## How to run (Google Colab)

1. Download all `.tif` files from the course server.
2. Create a folder named `Landsat_Zurich` in your Google Drive and place
   all `.tif` files there.
3. Open `urban_heat_zurich.ipynb` in Google Colab.
4. Run all cells. The notebook copies the data automatically.

## How to run (local)

pip install rasterio numpy pandas matplotlib geopandas osmnx
urban-heat-zurich/
├── urban_heat_zurich.ipynb
├── README.md
└── data/
   ├── LandsatComposite_Zurich_1985.tif
   ├── LandsatComposite_Zurich_1988.tif
   └── ...


