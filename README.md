# DATA420A1
ghcn-spark-analysis/
│
├── README.md
├── .gitignore
├── environment.yml or requirements.txt
│
├── notebooks/
│   ├── 01_data_exploration.ipynb
│   ├── 02_data_loading_and_schema.ipynb
│   ├── 03_data_enrichment.ipynb
│   ├── 04_missing_station_check.ipynb
│   ├── 05_station_analysis.ipynb
│   ├── 06_geospatial_distance.ipynb
│   ├── 07_daily_summary_analysis.ipynb
│   └── 08_visualisations.ipynb
│
├── scripts/
│   ├── load_schemas.py
│   ├── enrich_stations.py
│   ├── compute_distances.py
│   └── visualisation_helpers.py
│
├── data/
│   ├── raw/         # symbolic links or notes to Azure paths
│   ├── processed/   # outputs from Spark saved to local for visualisation
│   └── sample/      # small test subsets (optional)
│
├── output/
│   ├── figures/
│   ├── tables/
│   └── results/
│
└── report/
    ├── DATA420_Report.pdf
    └── supplementary_material.zip
