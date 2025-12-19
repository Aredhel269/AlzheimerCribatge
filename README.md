# PF_Monzo_Gloria

Estructura:

- data/raw/: dades originals
- data/processed/: dades netejades
- notebooks/: notebook principal
- scripts/: scripts auxiliars
- models/: models guardats (joblib)
- figures/: figures per l'informe
- reports/: informe final en PDF

Com reproduir:

1. Col·locar `alzheimers_disease_data.csv` a data/raw/.
2. Obrir el fitxer .ipynb de l'arrel i executar les cel·les en ordre.
3. Necessitats: 
    Python 3.9+
    pandas>=1.4.0
    numpy>=1.21.0
    scikit-learn>=1.0.0
    xgboost>=1.5.0
    matplotlib>=3.5.0
    joblib>=1.1.0