# Data Refinement Project — Cafe Sales (Dirty Data)

## Objectif
Nettoyer et transformer un dataset brut afin d'obtenir une donnée cohérente, exploitable et justifiée.

## Structure du projet
DATA-REFINEMENT-PROJECT/
├── DATA/
│   ├── RAW/
│   │   └── dirty_cafe_sales.csv
│   └── PROCESSED/
│       ├── clean_cafe_sales.csv
│       └── final_cafe_sales.csv
├── NOTEBOOKS/
│   ├── 01_EXPLORATION.ipynb
│   ├── 02_CLEANING.ipynb
│   └── 03_TRANSFORMATION.ipynb
├── REPORTS/
│   └── rapport.pdf
├── README.md
└── requirements.txt

## Installation
```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
