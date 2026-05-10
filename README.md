# Prizm — rapports publiés

> *« Faire passer les projets crypto au prizm »*

Ce repository contient les **rapports d'analyse Prizm** publiés en HTML
self-contained et PDF, accessibles via [GitHub Pages](https://samolower.github.io/prizm-reports/).

Chaque rapport décompose un projet crypto en **6 piliers d'analyse** (sécurité,
tokenomics, adoption, équipe & gouvernance, concurrence, conformité) selon la
méthodologie Prizm (édité par **Crypto FR**).

Le code source de Prizm reste privé : https://github.com/Samolower/Prizm

## 📚 Index

L'index automatique de tous les rapports : [index.html](https://samolower.github.io/prizm-reports/)

## Structure

```
prizm-reports/
├── index.html            # Index auto-généré (liste tous les rapports)
└── YYYY/
    └── MM/
        ├── YYYY-MM-DD_<slug>_analysis.html   # Version web (self-contained)
        └── YYYY-MM-DD_<slug>_analysis.pdf    # Version imprimable
```

## Publication

Les rapports sont publiés automatiquement par `scripts/publish_report.py` du
repo Prizm. Voir le README de Prizm pour la chaîne de production.
