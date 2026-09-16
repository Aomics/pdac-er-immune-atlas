# PDAC-ER-Immune Atlas

## Pregunta biológica / clínica

¿Cómo se relacionan las firmas de estrés de retículo endoplásmico (ER stress / UPR) con los programas de evasión inmune en el microambiente tumoral del adenocarcinoma ductal de páncreas (PDAC), y pueden usarse para estratificar pacientes según fenotipo inmune-metabólico?

## Estado

🚧 Estructura base del repositorio. Contenido en desarrollo.

## Estructura del repositorio

```
pdac-er-immune-atlas/
├── README.md
├── LICENSE
├── CITATION.cff
├── environment.yml
├── containers/
│   └── Dockerfile
├── workflow/
│   ├── main.nf
│   ├── nextflow.config
│   ├── modules/
│   └── test_data/
├── conf/
│   ├── base.config
│   ├── docker.config
│   └── singularity.config
├── assets/
│   ├── metadata_dictionary.csv
│   └── project_diagram.svg
├── data/
│   └── README.md
├── scripts/
│   ├── R/
│   └── python/
├── notebooks/
│   └── 01_exploratory_analysis.ipynb
├── results/
│   └── README.md
├── reports/
│   └── technical_report.qmd
└── .github/
    └── workflows/
        └── ci.yml
```

## Autor

Adrián Aguilera Martín — Bioinformático (Biología Sanitaria; Máster en Bioinformática y Análisis de Datos Biomédicos).

## Licencia

Ver [LICENSE](LICENSE).
